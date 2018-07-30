## Location
ap-northeast-2 (asia / seoul region)

## Info
before-upgrade : x1.16xlarge * 2 + m5.4xlarge
after-upgrade : x1.32xlarge * 2 + m5.4xlarge
349 ECU, 128vCPUs, 2.3 GHz, Intel Xeon E7 8880 v3, 1952 GB Memory, 2 x 1920GB SSD Storage, 25G bandwidth + 2 x 1920GB EBS Storage (auto-backup)

Use EBS snapshot backup. mount EBS Volume & rsync & snapshot (auto-backup)
Use AWS-CloudWatch statue check and Auto-Recovery
