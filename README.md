## Cadre du projet

L’objectif de ce TP est de mettre en place une autorité de certification basée sur OpenSSL disposant des services
suffisants pour permettre des demandes et déploiement de certificats de manière simple et efficace.
Afin d’avoir un contrôle plus précis sur la délivrance de certificats au sein d’un réseau local, vous mettrez en
place une PKI dans l’objectif de compléter celle fournie par le système Windows Server.

## Description

Ce playbook Ansible va ainsi permettre de lier le server Ubuntu qui hébergera notre PKI au domaine Active Directory (Windows Server 2016).

(Merci à [Tvories](https://github.com/tvories/ansible-realmd) pour son répo !)
