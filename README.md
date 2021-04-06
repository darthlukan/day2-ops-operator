# day2-operator

Author: Brian Tomlinson <btomlins@redhat.com>

# Description

An Ansible Operator which automates Day 2/Post-install Operations not handled by existing Operators on OpenShift/Kubernetes clusters.

The purpose of this operator is not to replace the functionality of other operators, it is to compliment them and fill
in the gaps in post-installation operations which still require manual intervention by the user. Where there is overlap
between Day2 Operator and others, users should defer to the more robust, purpose-built operator and rely on the functionality 
of this operator solely for proof of concepts or trivial, short-lived, non-production clusters, such as sandboxes.

This operator strives to be as simple as possible with the bulk of its functionality being akin to running `oc apply -f
${MANIFEST}.yaml`.

# Usage

TBD

# License

Apache 2.0, see LICENSE file.
