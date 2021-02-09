Master
=========

This role is going to help you in creating your instance as a **Kubernetes Master Node**

Requirements
------------

You have to upload your **ssh_private_key_file** in files folder of the role in place of **akki.pem**.

Dependencies
------------

You can use **Kube-worker** role for Configuration of instance as a **Worker Node** of **Kubernetes**.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
I am showing an example of Setup Playbook for an **AWS Instance** whose tag is `Name=master`.

    - hosts: tag_Name_master
      roles:
         - master


Author Information
------------------

**Aakash Choudhary**
[Contact Me](choudharyaakash316@gmail.com)
