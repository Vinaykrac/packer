**Packer**:	Packer is an Infrastructure as Code (IaC) tool by HashiCorp used to automate the creation of reusable machine images (AMIs, Azure Images, GCP Images, Docker Images, etc.).
**Build**: A build block defines which image source(s) to use, which provisioners to execute, and which post-processors to run to produce the final image.
**Provisioner**: Provisioners execute scripts or configuration management tools (Shell, Ansible, Chef, Puppet, etc.) to install packages, configure the operating system, and prepare the machine image. 
**Variable**: Variables make Packer templates reusable by allowing values such as region, instance type, AMI name, and credentials to be supplied at runtime instead of being hardcoded.
**Parallel Builds**: Packer can build multiple images simultaneously (for example, Ubuntu, RHEL, and Amazon Linux) using multiple source blocks within a single build, reducing image creation time. 
**Post-Processors**: Post-processors run after the image is created to perform tasks such as generating a manifest, creating checksums, compressing artifacts, or publishing images to registries.
