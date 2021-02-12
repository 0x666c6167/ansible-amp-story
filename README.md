# Ansible - AMP Story

This is an Ansible playbook for easily publishing an AMP Story based on an Imgur Album.

You will need: 

- An Imgur `clientId` to access their API 
- An ansible vault containing sensitive variables : 
    - Your Imgur `clientId`
    - The Imgur album hash `albumHash`

The AMP Story will be composed of `n` pages (`n` is the length of your Imgur Album) and add automatically the `title` and `description` of each image.

To know how to build an AMP Story, follow this [link](https://amp.dev/about/stories/).