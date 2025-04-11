# 🌟 Automate LAMP Stack with Ansible

Welcome to the **Automate LAMP Stack** project! This Ansible playbook brings a **Linux, Apache, MySQL, PHP (LAMP)** stack to life on your localhost, crafting a web server ready to spark your creativity. With a focus on simplicity, modularity, and reliability, it’s designed to make your deployment smooth, joyful, and inspiring.

I’m endlessly grateful to share this with you—thank you for joining me on this journey! 🙏 Your passion for learning fuels this project, and I hope it lights up your DevOps path with excitement.

---

## ✨ What This Project Does

This playbook automates a full LAMP stack setup, perfect for development, testing, or learning:
- **Apache**: Serves a cheerful `index.php` to confirm PHP is working flawlessly.
- **MySQL**: Installs a secure database with a root password, removing anonymous users and test databases.
- **PHP**: Powers dynamic web content, seamlessly linked with Apache.

**Why it’s special**:
- **Roles**: Organized into `apache`, `mysql`, and `php` for clarity and reuse.
- **Error Handling**: Uses `block`, `rescue`, and `always` to catch issues gracefully.
- **Handlers**: Restarts services like Apache and MySQL only when needed.
- **Modularity**: Tasks are split logically, making updates a breeze.

---

## 🛠️ Setup Instructions

Let’s get your LAMP stack shining bright! Follow these steps to prepare your Ubuntu machine.

### Prerequisites
- **Operating System**: Ubuntu (tested on 20.04/22.04).
- **Ansible**: Install it with:
  ```bash
  sudo apt update && sudo apt install ansible
  
## ❤️ Thank You
    

