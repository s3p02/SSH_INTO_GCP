# USING MAC OS or Linux

Open a new terminal.

# Step 1: Using the SSH-Key generated

```
sudo ssh -i ~/.ssh/gcp_deeplearn_gpu srpa3180@35.203.187.5
```

<kbd>
  <img src="/SSH_LOGIN_2_instance_1.png">
</kbd>

# Step 2: Confirm if GPU is attached

```
lspci
```

<kbd>
  <img src="/SSH_LOGIN_CONFIRM_GPU.png">
</kbd>

It's recommended that one stops the VM when its not used, as the charge per hour is ~$1. Approzimately you can get less than 300 hours with the free credit to play around with a GPU VM on GCP.
