# vars.yml
```bash
# Common variables for Raspberry Pi NAS setup
nas_endpoint: "192.168.1.10"             # The IP address or hostname of the NAS endpoint
nas_user: "user"                         # Username for NAS authentication
nas_password: "password"                 # Password for NAS authentication
nas_port: 22                             # Port number for SSH or other service communication
ssh_private_key_path: "/path/to/ssh/key" # Absolute path to the private SSH key
ansible_ssh_common_args: "-o StrictHostKeyChecking=no" # SSH common arguments
local_path_git: "path/to/git/repo/root" # Local path to the git repository
```