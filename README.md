# setup-datascience-environment-gcp
Step by step how to setup a data science environment on Google Cloud

## Create a GCE instance
Navigate to the VM instances page. You'll be asked to login with your Google credentials and create a project. Once you've done that, you'll be taken to the VM instances page:

To create a new virtual instance, click Create Instance. You'll be taken to a page where you can customize different properties of the instance you want to rent:


**```Name:```** Naming your instance. We just used the default name.

**```Zone:```** Which geographic zone your server lives. We used us-east1-b but feel free to select an instance closer to where you live or work.

**```Machine Type:```** How powerful of a machine you want to rent. Recall that you can read about the different machine types from this page. Choose one within your monthly budget!

**```Boot Disk:```** The operating system you want the virtual instance to boot with. We used Ubuntu 16.04 LTS, which is a popular Linux version.

**```Firewall:```** What internet traffic should be allowed in. Leave this with the default settings.

Click **Create** when you're ready.

## Setting up the data science environment## 
After you've launched a Google Compute Engine instance, you can actually launch a console right from the Google Compute Engine page:

We'll use this console to setup the rest of the data science environment.

