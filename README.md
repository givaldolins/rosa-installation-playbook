# arctiq-mission
A repository used to store code for my Arctic mission   ![badge](https://img.shields.io/badge/version-v1.0.0-success)

## Prerequisites:
- An AWS account configured for supporting OpenShift Rosa [link](https://docs.openshift.com/rosa/rosa_getting_started_sts/rosa-sts-aws-prereqs.html);
- A Red Hat account [[link]](access.redhat.com);
- Enable ROSA in your AWS console [[link]](https://console.aws.amazon.com/rosa);
- A ROSA Token: [[link]](https://console.redhat.com/openshift/token/rosa);
- The following tools installed in the machine that will run this playbook:
  - AWS CLI [[link]](https://aws.amazon.com/cli/);
  - ROSA CLI [[link]](https://www.openshift.com/products/amazon-openshift/download);
  - OpenShift CLI [[link]](https://mirror.openshift.com/pub/openshift-v4/x86_64/clients/oc/latest/);

## Usage:
```bash
$ git clone https://github.com/givaldolins/arctiq-mission
$ ansible-playbook deploy-cluster.yaml --ask-vault-password -vvv
```