# ocp4_aap


From a terminal, go to your <playbook_dir> directory.

Set the KUBECONFIG environment variable with the following command:

export KUBECONFIG=kubeconfig

Log into your Red Hat OpenShift with oc login and generate your kubeconfig file. Run the following command:

oc login <openshift console> -u <username> -p <password>

List the files in your directory and confirm that your kubeconfig file was created.

Verify the content of the kubeconfig file. Be sure that you have one value for clusters, one value for contexts, and one value for users.


