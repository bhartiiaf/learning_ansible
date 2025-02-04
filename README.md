# learning_ansible

Welcome to the **Ansible Learning Repository**! This repository is designed to help individuals to learn and practice Ansible, an open-source automation tool used for configuration management, application deployment, and orchestration. Whether you are a beginner or looking to enhance your Ansible skills, this repository will serve as a comprehensive guide.

Note: If you found the content helpful, please consider giving this repository a star ⭐
---

## Repository Structure

The repository is structured into the following directories:

1. **`01-Introduction`**: 
   - Basics of Ansible.
   - Installation steps for different operating systems.
   - Key terminologies (e.g., Inventory, Playbooks, Modules).

2. **`02-Basic-Playbooks`**:
   - Writing your first playbook.
   - Understanding YAML syntax.
   - Executing simple tasks (e.g., file creation, service restart).

3. **`03-Modules`**:
   - Detailed examples of commonly used Ansible modules (e.g., `file`, `command`, `copy`, `user`).
   - Working with community modules.

4. **`04-Variables-and-Facts`**:
   - Introduction to variables.
   - Using facts to gather system information.
   - Defining variables in inventories and playbooks.

5. **`05-Roles`**:
   - Structuring roles for modular automation.
   - Role directory structure and best practices.
   - Sharing roles with `ansible-galaxy`.

6. **`06-Conditionals-and-Loops`**:
   - Using conditionals (`when` statement).
   - Iterating over tasks using loops (`with_items`, `with_dict`, etc.).

7. **`07-Advanced-Features`**:
   - Using Ansible Vault for securing sensitive data.
   - Managing large inventories with dynamic inventory scripts.
   - Error handling and debugging.

8. **`08-Real-World-Examples`**:
   - Automating infrastructure deployment.
   - Application deployments (e.g., web servers, databases).
   - Configuring CI/CD pipelines with Ansible.

9. **`09-Troubleshooting`**:
   - Common issues and their resolutions.
   - Tips and tricks for debugging playbooks.

10. **`10-References`**:
    - Links to official documentation, blogs, and community forums.

---

## Prerequisites

Before diving into this repository, ensure you have the following:

- Basic understanding of Linux/Unix systems.
- Python installed on your local system.
- Ansible installed (follow the instructions in `01-Introduction`).

---

## Getting Started

### 1. Clone the Repository

```bash
# Clone the repository
$ git clone https://github.com/bhartiiaf/learning_ansible.git

# Navigate into the repository
$ cd ansible-training
```

### 2. Install Dependencies

Some examples may require specific dependencies. Install them as follows:

```bash
# Install required Python packages (if needed)
$ pip install -r requirements.txt
```

### 3. Run Your First Playbook

Navigate to `02-Basic-Playbooks` and execute your first playbook:

```bash
# Run a sample playbook
$ ansible-playbook hello-world.yml -i inventory.ini
```

---

## Contribution Guidelines

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   $ git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   $ git commit -m "Add your message here"
   ```
4. Push your branch and create a Pull Request (PR).

For more details, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

---

## License

This repository is open-sourced. Feel free to use and share it.

---

## Support

If you have any questions or need support, feel free to open an issue or contact the repository maintainer.
