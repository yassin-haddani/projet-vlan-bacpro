# 📡 Schéma réseau – Projet VLAN

## VLAN configurés

- VLAN 10 : ADMIN
- VLAN 20 : TECH

## Attribution des ports

- FastEthernet 0/1 → VLAN 10
- FastEthernet 0/2 → VLAN 20

## Objectif de segmentation

Chaque VLAN est isolé.
Les machines du VLAN 10 ne peuvent pas communiquer avec celles du VLAN 20 sans routage inter-VLAN.

## Test réalisé

- Ping intra-VLAN : OK
- Ping inter-VLAN : Échec (isolement fonctionnel)
