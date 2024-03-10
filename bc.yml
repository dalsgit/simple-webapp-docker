apiVersion: build.openshift.io/v1
kind: BuildConfig
metadata:
  name: my-build-config
spec:
  runPolicy: Serial
  source:
      git:
        ref: master
        uri:
      type: Git
  strategy:
      sourceStrategy:
      type: Source
  output:
    to:
      kind:
      name:
  triggers:
    - type: ConfigChange
