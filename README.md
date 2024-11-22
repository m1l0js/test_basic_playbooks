# **📦 Test Basic Playbooks**

Welcome to **Test Basic Playbooks**, a collection of **Ansible playbooks** designed to automate common day-to-day tasks across various Linux distributions. These playbooks are free to use, modify, and distribute under an open license.

---

## **✨ Features**
- 🛠️ **Manage packages**: Install, uninstall, or upgrade packages based on your distro.
- 📂 **Copy files**: Automate file transfers with ease.
- 🔄 **Update systems**: Keep your systems up-to-date without hassle.
- 🖥️ **Execute scripts**: Run custom scripts on remote hosts.
- 🔍 **Check processes**: Ensure critical processes are running.
- 👤 **Create admin users**: Add users with administrative privileges tailored to different distros.
- 🗑️ **Delete users**: Remove users completely, along with their files and configurations.

---

## **📂 Playbooks Overview**

| Playbook                     | Description                                                        |
|------------------------------|--------------------------------------------------------------------|
| `01_manage_packages.yml`     | Install and remove packages on Debian, RHEL, and other distros.   |
| `02_copy_files.yml`          | Automate file transfers to remote hosts.                          |
| `03_update_hosts.yml`        | Update package caches on Debian, RHEL, and FreeBSD.               |
| `04_execution_scripts.yml`   | Run custom scripts on managed hosts.                              |
| `05_check_process.yml`       | Check the status of running processes.                            |
| `06_create_admin_user.yml`   | Create an admin user (`bos`) with secure password and admin group. |
| `07_delete_user.yml`         | Remove a user completely (`bos`) and ensure only one admin user.  |

---

## **📖 How to Use**
1. Clone this repository:
   ```bash
   git clone https://github.com/m110js/test_basic_playbooks.git
   ```
2. Navigate to the directory:
   ```bash
   cd test_basic_playbooks
   ```
3. Run any playbook using `ansible-playbook`:
   ```bash
   ansible-playbook -i inventory <playbook_name>.yml
   ```

---

## **🛑 Requirements**
- Ansible 2.9 or later.
- SSH access to target hosts.
- Properly configured `inventory` file.

---

## **📜 License**

This repository is licensed under the **MIT License**. You are free to use, copy, modify, and distribute this code with no restrictions.

> **MIT License**
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## **🌟 Contributions**

Contributions are welcome! Feel free to:
- Submit issues.
- Fork and submit pull requests.
- Share your feedback.

---

## **📧 Contact**
For any questions or support, reach out via [GitHub Issues](https://github.com/m110js/test_basic_playbooks/issues).
