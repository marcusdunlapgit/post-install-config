<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## 🔧 Post-Installation Configuration

After installing osTicket, follow these configuration steps to set up roles, departments, teams, and permissions for agents and users.

---

### 🔹 Admin & End-User URLs

- **Admin/Analyst Login Page:**  
  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Admin Login Page Screenshot"/>

- **End User Portal URL:**  
  [http://localhost/osTicket](http://localhost/osTicket)

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="End User Portal Screenshot"/>

---

### 🔹 Acknowledge: Agent Panel vs Admin Panel

- **Agent Panel**: Used for ticket handling, responses, and internal notes.  
- **Admin Panel**: Used for managing system settings, roles, teams, departments, and agents.

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Agent vs Admin Panel Screenshot"/>

---

### 🔹 Configure Roles (Group-based Permissions)

**Path:** `Admin Panel → Agents → Roles`

- Example Role: `Supreme Admin` (Full permissions)

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Configure Roles Screenshot"/>

---

### 🔹 Configure Departments (Ticket Visibility Scope)

**Path:** `Admin Panel → Agents → Departments`

- Examples:
  - `Help Desk`
  - `SysAdmins`
  - `Networking`

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Departments Configuration Screenshot"/>

---

### 🔹 Configure Teams (Cross-Department Collaboration)

**Path:** `Admin Panel → Agents → Teams`

- Example Team: `Online Banking` (includes agents from multiple departments)

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Teams Configuration Screenshot"/>

---

### 🔹 Allow or Restrict Ticket Creation for Unregistered Users

**Path:** `Admin Panel → Settings → User Settings`

- ✅ **Uncheck**: *Unregistered users can create tickets*  
- ✅ Enable: *Registration Required*

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="User Settings Screenshot"/>

---

### 🔹 Configure Agents (Internal Staff)

**Path:** `Admin Panel → Agents → Add New`

- **Jane** (Department: `SysAdmins`)  
- **John** (Department: `Support`)

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Add Agent Screenshot"/>

---

### 🔹 Configure Users (Customers / External Users)

**Path:** `Agent Panel → Users → Add New`

- **Karen**  
- **Ken**

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Add Users Screenshot"/>

---

### 🔹 Configure SLA (Service Level Agreements)

**Path:** `Admin Panel → Manage → SLA`

- **Sev-A**  
  - Grace Period: `1 hour`  
  - Schedule: `24/7`

- **Sev-B**  
  - Grace Period: `4 hours`  
  - Schedule: `24/7`

- **Sev-C**  
  - Grace Period: `8 hours`  
  - Schedule: `Business Hours`

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="SLA Configuration Screenshot"/>

---

### 🔹 Configure Help Topics

**Path:** `Admin Panel → Manage → Help Topics`

- **Business Critical Outage**  
- **Personal Computer Issues**  
- **Equipment Request**
- **Password Reset**  
- **Other**

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Help Topics Configuration Screenshot"/>

---

## 🏁 Final Notes

Your osTicket system is now configured and operational. Be sure to test workflows from both the end-user and admin perspectives to ensure proper routing, SLA tracking, and role visibility.

---

## 📝 Author

**Marcus Dunlap**  
📧 [me@marcusdunlap.tech](mailto:me@marcusdunlap.tech)
