# Backup & Cleanup Automation

This project provides an automated system to back up files, compress them for retention, and manage cleanup using Bash and YAML configuration.  
The YAML file allows you to change backup destinations without modifying the Bash script, making the setup flexible and easy to maintain.

---

## 📂 Project Structure

backupproject/
├── config.yml          # Configuration file (source & destination paths)
├── backupscript.sh     # Bash script to run backups
├── backupfolder/       # Stores raw backup files
└── backups/            # Compressed backups for log retention



---

## 📝 Steps Involved
1. Create the main folder `backupproject`.
2. Inside it, create two subfolders:
   - `backupfolder` → to store backup files
   - `backups` → to store compressed backups for retention
3. Add `config.yml` in `backupproject` to define source and destination paths.
4. Add `backupscript.sh` in `backupproject` to run the backup process.
5. Make the script executable
6. Run the script to generate backups
7. Verify that the latest backup file appears in the backups folder
