Here, we can use volumes to data persistent for kubernetes pods. so we are going to explore different types of volumes in kubernetes.

- emptyDir
  it will create a empty directory on the pod and it will be deleted when the pod is deleted. it is used for temporary storage.

- hostPath
  it will mount a file or directory from the host node's filesystem into your pod. it is used for development and testing.
