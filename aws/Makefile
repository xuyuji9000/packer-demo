validate:
	packer validate example.json
build:
	packer build example.json

show-image:
	aws ec2 describe-images --filters "Name=image-id,Values=ami-0220b23b"

get-16:
	aws ec2 describe-images --filters "Name=name,Values=*ubuntu*16.04*201703*" "Name=architecture,Values=x86_64" "Name=virtualization-type,Values=hvm"
