# Periodic Table Database

This project uses PostgreSQL to store information about chemical elements.

## How to run

Run the script with an element's atomic number, symbol, or name:

```bash
./element.sh 1
./element.sh H
./element.sh Hydrogen
```

The script displays the element's atomic number, name, symbol, type, atomic mass, melting point, and boiling point.

## Database Backup

The database backup is stored in `periodic_table.sql`.
