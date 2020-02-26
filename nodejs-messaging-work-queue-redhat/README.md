Open up the openshift connector terminal and login to your openshift cluster:

`odo login ${your cluster url}`

Once logged in:
inside of your terminal navigate to /projects/nodejs-messaging-work-queue and run `oc create -f service.amqp.yaml`
