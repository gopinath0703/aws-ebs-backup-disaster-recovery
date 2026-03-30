# 💾 Backup and Disaster Recovery using EBS Snapshots

## 📌 Project Overview
Implemented a backup and disaster recovery strategy using Amazon EBS Snapshots.
Simulated a real-world failure scenario and successfully restored data,
ensuring business continuity.

## 🛠️ AWS Services Used
- Amazon EC2
- Amazon EBS (Elastic Block Store)
- EBS Snapshots
- Amazon S3 (Snapshot storage)
- Security Groups

## 📋 Steps Followed
1. Launched EC2 instance and attached EBS volume
2. Stored critical application data on EBS volume
3. Created EBS snapshot as backup
4. Simulated failure by deleting the original EBS volume
5. Restored data by creating new volume from snapshot
6. Attached restored volume to EC2 instance
7. Verified data recovery and business continuity

## 📈 Results
- Successfully recovered 100% of data from snapshot
- Achieved near-zero data loss using snapshot strategy
- Demonstrated real-world disaster recovery process
- Ensured business continuity after simulated failure

## 🏗️ Architecture
EC2 + EBS Volume → Create Snapshot → Simulate Failure 
→ Restore Volume from Snapshot → Attach to EC2 → Data Recovered ✅

## 💡 Key Learnings
- EBS Snapshots are cost-effective backup solutions
- Regular snapshots minimize data loss in disaster scenarios
- Recovery time depends on volume size and snapshot age

## 👨‍💻 Author
**Gopinath T** — AWS Certified Solutions Architect
- GitHub: https://github.com/gopinath0703
- Email: gopinathdhanasampath23@gmail.com
