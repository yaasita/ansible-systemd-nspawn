#!/bin/bash
set -eu
# iptables
iptables -F -t nat
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE
