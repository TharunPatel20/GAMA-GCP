# Capstone Project Solution-1

Below are the images demonstrating my solution for the GCP Capstone Project (Lab-7).

### Phase 1: Foundation (Network & Identity)

**1.1: VPC [Virtual Private Cloud]**  
![GCP capstone project Solution](images/1-1_VPC.png)

**1.2: Firewall Rules**  
![GCP capstone project Solution](images/1-2_firewall-rules.png)

**1.3: Service Account**  
![GCP capstone project Solution](images/1-3_Service-Account.png)

---

### Phase 2: Content Storage

**2.1: Cloud Storage Bucket**  
![GCP capstone project Solution](images/2-1_cloud-storage-bucket.png)

**2.2: Adding Permission to Bucket**  
![GCP capstone project Solution](images/2-2_bucket-permission.png)

**2.3: Upload to Bucket**  
![GCP capstone project Solution](images/2-3_upload-to-bucket.png)

---

### Phase 3: Compute (Web Server)

**3.1: VM Instance Setup**  
![GCP capstone project Solution](images/3-1_VM-instance.png)

**3.2: Startup Script & Deployment**  
![GCP capstone project Solution](images/3-2_startup-script.png)

<!-- **3.3: Dashboard Verification**  
![GCP capstone project Solution](images/3-3_dashboard.png) -->

---

### Phase 4: Observability

**4.1: Monitoring Dashboard**  
![GCP capstone project Solution](images/4-1_monitoring-dashboard.png)

**4.2: Alert Policy Configuration**  
![GCP capstone project Solution](images/4-2_alert-policy.png)

**4.3: Applying Labels**  
![GCP capstone project Solution](images/4-3_labels.png)

---

### Phase 5: Content Update Flow

**Dashboard Reflecting New Content**  
![GCP capstone project Solution](images/5_dashboard-updated.png)

---

### Key Takeaways

- Multi-service integration: VPC, Compute Engine, Cloud Storage, IAM, Monitoring, and Logging work together seamlessly.
- Decoupled content: Cloud Storage allows IT to update the dashboard without touching servers.
- Service accounts: Use VM-attached identity to securely access Storage without storing credentials.
- Observability: Monitoring dashboards, alerts, and labels ensure production readiness.
- End-to-end validation: Full flow tested, including content updates and security checks.

---