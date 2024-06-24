# sway-vnc-scripts
Repository of scripts to assist management of a self-hosted one server to many clients sway VNC setup


# Usage

server & desktop are used exchangably here.

1. set-up port forwarding on your router.
2. configure .ssh/config.d/desktop-public, with IP & port information
    - make sure to run ssh-copy-id & that you are able to sign in to your desktop using `ssh desktop`
3. run `vnc_server_start`
4. on client run `vnc_server_connect`
    - and `vnc_server_disconnect` after you are done

# Requirements

* knowledge of how ssh works,
* able to do port forwarding in your network
* install autossh


Enjoy!
