# Creating a Directory 
  mkdir <dir_name>

# Switching a Directory
  cd <dir_name>

# Creating an empty file
  touch <file_name>

# Creating a file using Vi editor
  vi <file_name>
  --> add the content -->
  press ESC + :wq <-- for save and exit
  press ESC + :q! <-- for quit without saving

# Displaying the file content
  cat <file_name>

# removing the file
  rm -rf <file_name>

# removing the empty directory
  rmdir <dir_name>

# Check hostname or server name
  hostname

# Check system or server time
  uptime

# Check Available Memory
  free -gh

# Text Search
  grep -r "pattern" /path/to/search

# System Information
  uname -a
  cat /etc/os-release

# Network Information
  ifconfig
  netstat -tulpn

# Package Management
  apt-get update
  apt-get install <package_name>

# User Management:
  useradd <username>
  passwd <username>

# switch user
  su <username>
  exit to quit from other user

# File Permissions
  chmod +x <file_name>
  chmod 775 <file_name>
  chown user:group <file_name>

# System Logs:
  tail -f /var/log/syslog

# Firewall Configuration
 ufw allow 80