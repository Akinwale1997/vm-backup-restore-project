# 🔄 Azure VM Backup and Restore Project

This project demonstrates a full backup and restore cycle for an Azure Virtual Machine using Recovery Services Vault. It reflects real-world disaster recovery practices.

---

## ✅ Scenario

> As a Cloud Security Engineer tasked with safeguarding critical infrastructure. In this scenario, you need to back up a running VM and verify your organization's disaster recovery plan by restoring it from a recovery point.

---

## 🧰 Tools & Resources

- Azure Virtual Machine (Windows Server 2019)
- Recovery Services Vault (mayaVault)
- Azure Backup Policy (Enhanced)
- Azure Storage Account (Staging Location)

---

## 🚀 Steps Performed

### 1. VM Backup Created  
Deployed BackupTestVM and prepared it for backup.  
![VM Backup Created](01-vm-backup-created.png)

---

### 2. Recovery Vault Setup  
Created Recovery Services Vault named mayaVault.  
![Vault Create](02-vault-create.png)

---

### 3. Backup Configuration  
Configured enhanced policy and backup settings for the VM.  
![Backup Config](03-backup-config.png)

---

### 4. Backup Enabled  
Enabled backup for the VM using the new policy.  
![Backup Enabled](04-backup-enabled.png)

---

### 5. Backup Job Status  
Monitored and confirmed the backup job completed successfully.  
![Backup Job Status](05-backup-job-stattus.png)

---

### 6. Restore Point Confirmed  
Verified the restore point was successfully generated.  
![Restore Point Confirmed](06-restore-point-confirmed.png)

---

### 7. VM Restore Setup & Review  
Restored the VM using the recovery point, setting new name and resources.  
![VM Restore Review](07-vm-restore-review.png)

---

### 8. VM Restore Succeeded  
Restore completed. Verified restored VM is up and healthy.  
![VM Restore Succeeded](08-vm-restore-succeeded.png)

---

## ✅ Validation

All steps have been fully tested:
- The restored VM booted up successfully
- Health status is green
- Verified connectivity, OS status, and disk

Everything is running properly and as expected.

---

## 💡 Key Takeaways

- Azure Backup ensures data resiliency and quick disaster recovery
- Recovery Vault + Backup Policy offers automated and scheduled backups
- Testing the restore process is critical for business continuity

---
