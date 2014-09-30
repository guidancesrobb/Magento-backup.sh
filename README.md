# Magento File and Database Backup Script

Developed by Magento Core Team.

This script will create two files containing the Magento code and database.  The database will be dumped without log table contents and with obscured customer data.

## Example Usage

    cd /path/to/magento
    curl -O backup.sh https://raw.githubusercontent.com/guidancesrobb/Magento-backup.sh/master/backup.sh
    chmod +x backup.sh
    ./backup.sh
    
This will create a `.tar.gz` and `.sql.gz` with long, randomly generated names in the root of the application.



