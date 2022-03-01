# python-hello-world

A simple program that displays “Hello, World!”. It's often used to illustrate the syntax of the language.

To use the custom base image in "pipeline" project
oc policy add-role-to-user system:image-puller system:serviceaccount:opentlc-mgr-codeready:che-workspace -n pipeline
