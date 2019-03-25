# kubernetes-sandbox


1. Set your environment variables:
	- `export AWS\_SECRET\_KEY\_ID=`
	- `export AWS\_SECRET\_ACCESS\_KEY=`

2. Launch a docker container that mounts your directory (curtis style). The container has terraform installed, and then can be used to launch a cluster. 
	- `sh terraContainer.sh	`

3. 