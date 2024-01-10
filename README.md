# max-prefixes-calculator

We can use this script to calculate the number of prefixes the subnet can afford depending on the subnet CIDR so we can know why we get “InsufficientCidrBlocks” even there are available IPs.

## Usage:

```bash
 ./max-prefixes-calculator.sh --subnet-id <$subnet_id> --region <$region>
```

## OUTPUT:

```
SUBNET CIDR: 192.168.0.0/24
Network Interfaces:  1
Total IPs:  256
Allocated IPs:  38
Available IPs:  218
MAX /28 prefixes:  16
Possible /28 prefixes:  13
Prefixes In use:  2
Available Prefixes:  11
```

For more explanation about the outbut, we can use

```bash
./max-prefixes-calculator.sh -h
```
