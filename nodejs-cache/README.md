Inside of Eclipse Che open up the openshift connector terminal and login to your openshift cluster:

`odo login ${your cluster url}`

Once logged in:
inside of your terminal navigate to /projects/nodejs-cache and run `oc create -f service.cache.yaml`
