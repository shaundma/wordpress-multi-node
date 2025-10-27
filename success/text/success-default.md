# WordPress Multi-Node Kit Installed Successfully!

Your WordPress site is ready at: **${env.url}**

## Admin Login
- **URL**: ${globals.PROTOCOL}://${globals.DOMAIN}/wp-admin
- **Username**: admin
- **Password**: **${globals.WP_ADMIN_PASS}**

## Database
- **Host**: ${globals.DB_HOST}
- **Database**: wordpress
- **Username**: ${globals.DB_USER}
- **Password**: **${globals.DB_PASS}**

## Redis Cache
- **Host**: ${globals.REDIS_HOST}
- **Port**: ${globals.REDIS_PORT}
- **Password**: **${globals.REDIS_PSWD}**

**Security Note**: Change the admin password immediately after login.
