# Backups-The-foundation-of-Reliability

This project is a Bash-based backup script designed for automated server backups with a 5-day rotation policy. It creates timestamped .zip backups of a specified source directory and stores them in a designated backup folder. The script automatically keeps only the latest five backups, deleting older ones to optimize storage and maintain a clean backup environment.

The backup process is fully automated using cron jobs, ensuring that backups occur regularly without manual intervention. This automation is critical in a DevOps context because it enhances system reliability and data safety — protecting against accidental deletion, hardware failures, or data corruption. By automating backups and implementing rotation, the system is resilient, predictable, and easier to manage, which aligns with key DevOps principles of automation, reliability, and continuous operation.

As a DevOps engineer, implementing this script demonstrates practical skills in:
- Automating operational tasks using shell scripting.
- Managing backup rotation and storage efficiently.
- Enhancing reliability and availability of server data through automated processes.
- Integrating simple automation into existing system workflows (via cron).

Usage:
./backup.sh <source_directory> <backup_directory>


Requirements: Linux/macOS with Bash and the zip utility installed. The script should be made executable using:
chmod +x backup.sh
