
# Alpha Simulation - Installation Guide

Welcome! Follow the steps below to properly install and run the Alpha Simulation program on your Linux system.

---

## 📁 Files Required

Make sure the following three files are placed in the **same directory**:

1. `alpha_simulation`  
2. `install_tools.sh`  
3. `install_codes.sh`  

**⚠ All three files must be in the same folder before proceeding.**

---

##  Step-by-Step Installation

### 1️⃣ Make `install_tools.sh` executable

Open your terminal, navigate to the folder containing the files, and run:

```bash
chmod +x install_tools.sh
```

---

### 2️⃣ Run `install_tools.sh`

Now run the tool installer:

```bash
./install_tools.sh
```

This script installs necessary tools, dependencies.

---

### 3️⃣ Run `install_codes.sh`

Run the code setup script:

```bash
./install_codes.sh
```
This script places the alpha_simulation binary into the system path.

>  No need to use _`chmod`_ for this one.

---

##  Where is the program installed?

After the scripts run, the `alpha_simulation` executable will be installed to:

```
/usr/local/bin/alpha_simulation
```

This means it's now accessible system-wide from the terminal.

---

##  How to Run the Program

Simply type the following in your terminal:

```bash
alpha_simulation
```

And the graphical application will launch.

---

##  Notes

- Make sure you are connected to the internet during installation.
- If you face any permission errors, try using `sudo` or run the scripts as administrator.

---

Enjoy using _Alpha Simulation_!  
Created by **Alpha Team** – Tehran, Iran  
Contact: emadshojaee.sh@gmail.com
Channel: t.me/Alpha_Development_Team
