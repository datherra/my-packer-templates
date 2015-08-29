The `centos-7-x86_64-aws.box` file is just a result of:
`tar zcvf centos-7-x86_64-aws.box metadata.json Vagrantfle`

When not modifying standard AMIs, it doesn't make sense to use `packer` to create the images.
