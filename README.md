


```
1. 🔧 Install Requirements

ansible-galaxy collection install google.cloud
pip install requests google-auth


2. Ensure your service account has these roles:

roles/compute.admin

roles/iam.serviceAccountUser

roles/storage.objectViewer (for startup scripts in GCS)

3. 🚀 Run Playbook

ansible-playbook create-gce-instance.yml


``
# gce-instance-ansible-collection
