## Internal Development Guidelines 

A Cheqd node can be set up by following the [official documentation](https://docs.cheqd.io/node/docs/setup-and-configure). 

#### Monitor node status

Run `systemctl status cheqd-noded`. 

### Check node balance

Run `cheqd-noded query bank balances cheqd18zmlsmzx3s6a77ek0nyjjxztkjjmgj27ceqxu2`.

### Configuring cheqd node

Make sure you are in Cheqd system user. Run `sudo su cheqd` if you are not. 
