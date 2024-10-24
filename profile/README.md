## Hi there 👋

### About NexaMerchant
> NexaMerchant is a free ecommerce platform, base on Laravel framework.

### Nexa Merchant Laravel ecommerce Docker Compose [docker source](https://github.com/xxl4/NexaMerchant/tree/main/docker)

```bash
docker-compose up -d
```

## Application DB Migration and Seed
```bash
docker-compose exec nexamerchant-php-apache php artisan key:generate
docker-compose exec nexamerchant-php-apache php artisan migrate
docker-compose exec nexamerchant-php-apache php artisan db:seed
```

## Plugin Install

```bash
docker-compose exec nexamerchant-php-apache php artisan plugin:install shopify
```

## Plugin Uninstall

```bash
docker-compose exec nexamerchant-php-apache php artisan plugin:uninstall shopify
```

## Plugin List

```bash
docker-compose exec nexamerchant-php-apache php artisan plugin:list
```

## Plugin Update

```bash
docker-compose exec nexamerchant-php-apache php artisan plugin:update shopify
```

### How to Install (Docker)
```
docker pull nicesteven/nexamerchant:latest
```

### How to Install (Git)
```
git clone https://github.com/xxl4/NexaMerchant.git
```

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
