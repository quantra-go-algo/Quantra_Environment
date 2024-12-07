# Quantra Python Environments

This repository contains `.yml` files to help you set up Python environments for seamless dependency management in Quantra projects. Use these files to create and activate Python environments with all the necessary packages pre-installed.

For detailed guidance, refer to the [Setting Up Python On Your System](https://blog.quantinsti.com/set-up-python-system/) blog.

---

## 📥 How to Use

1. **Download the `.yml` File**:
   - Clone this repository or download the `.yml` file for the specific project you want to set up.

   OR

   - Use the `.yml` file directly from the repository link by providing its URL in the commands below.

2. **Install Anaconda**:
   - Download the Anaconda distribution suitable for your operating system from the [official Anaconda website](https://www.anaconda.com/products/distribution).
   - Follow the installation instructions for your system:
     - [Install Anaconda on Windows](https://blog.quantinsti.com/set-up-python-system/#install-anaconda-on-windows)
     - [Install Anaconda on Mac](https://blog.quantinsti.com/set-up-python-system/#install-anaconda-on-mac)
   - If you face any installation issues, check the [troubleshooting guide](https://blog.quantinsti.com/set-up-python-system/#troubleshooting-anaconda-installation-issues).

---

## ⚙️ Setting Up the Python Environment

1. **Create a New Environment from the `.yml` File**:
   - Open the Anaconda Prompt (Windows) or Terminal (Mac).
   - Navigate to the directory containing the desired `.yml` file.
   - Run the following command to create the environment (replace `environment.yml` with the correct file name):
     ```bash
     conda env create -f environment.yml
     ```
   - Alternatively, if using the `.yml` file directly from a URL:
     ```bash
     conda env create -f https://raw.githubusercontent.com/<user>/<repo>/main/<file>.yml
     ```

2. **Activate the New Environment**:
   - Activate the environment with:
     ```bash
     conda activate <environment_name>
     ```
   - Replace `<environment_name>` with the name specified in the `.yml` file.

3. **Verify the Environment**:
   - Check if the environment is created successfully by listing all environments:
     ```bash
     conda env list
     ```

---

## 🛠 Notes

- Always activate the appropriate environment before running your projects to ensure all dependencies are managed correctly.

---

## 🎉 Congratulations!

You’re ready to start using the Python environment for Quantra projects. For further guidance, refer to the **Folder Structure and How to Run Code Files.html** document included in the project files.

---

## 🛠 Facing Issues?

If you encounter any issues during setup, raise your query on the [Quantra Community](https://quantra.quantinsti.com/community) for assistance.

---

&copy; QuantInsti Quantitative Learning Private Limited
