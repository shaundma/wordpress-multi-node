# WordPress Multi-Node Kit Installed Successfully!

Dear User,

Your WordPress site is now live! Below are your login credentials and connection details.

## WordPress Admin
- **Site URL**: ${globals.PROTOCOL}://${globals.DOMAIN}
- **Admin URL**: ${globals.PROTOCOL}://${globals.DOMAIN}/wp-admin
- **Username**: admin
- **Password**: **${globals.WP_ADMIN_PASS}**

## Database (MariaDB)
- **Host**: ${globals.DB_HOST}
- **Database Name**: wordpress
- **Username**: ${globals.DB_USER}
- **Password**: **${globals.DB_PASS}**

## Redis Cache
- **Host**: ${globals.REDIS_HOST}
- **Port**: ${globals.REDIS_PORT}
- **Password**: **${globals.REDIS_PSWD}**

## Environment Details
- **CP Node**: ${nodes.cp.master.address}
- **DB Node**: ${nodes.sqldb.master.address}
- **Cache Node**: ${nodes.cache.master.address}

**Next Steps**:
1. Log in to WordPress and change the admin password.
2. Configure SSL (if not enabled) in the Jelastic dashboard.
3. Install themes/plugins as needed.

If you have questions, contact support.

Best regards,  
Jelastic Team
