Kustomize configuration files for deployment to AWS EKS
- Config files for [express-app](https://github.com/Lisa-Stats/express-app)
- Infrastructure for EKS cluster created with `terraform` here:
  - [tf-aws-eks](https://github.com/Lisa-Stats/tf-aws-eks)
<!DOCTYPE html>
<html>
<head>
<body>
	<h1>Structure</h1><p>
	├── <a href="/base/">base</a><br>
	│   ├── <a href="/base/creds.txt">creds.txt</a><br>
	│   ├── <a href="/base/express-deployment.yaml">express-deployment.yaml</a><br>
	│   ├── <a href="/base/express-ingress.yaml">express-ingress.yaml</a><br>
	│   ├── <a href="/base/express-service.yaml">express-service.yaml</a><br>
	│   └── <a href="/base/kustomization.yaml">kustomization.yaml</a><br>
	├── <a href="/overlays/">overlays</a><br>
	&nbsp;&nbsp;&nbsp; ├── <a href="/overlays/dev/">dev</a><br>
	&nbsp;&nbsp;&nbsp; │   ├── <a href="/overlays/dev/dev.env">dev.env</a><br>
	&nbsp;&nbsp;&nbsp; │   ├── <a href="/overlays/dev/kustomization.yaml">kustomization.yaml</a><br>
	&nbsp;&nbsp;&nbsp; │   └── <a href="/overlays/dev/namespace.yaml">namespace.yaml</a><br>
	&nbsp;&nbsp;&nbsp; └── <a href="/overlays/testing/">testing</a><br>
	&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <a href="/overlays/testing/kustomization.yaml">kustomization.yaml</a><br>
        &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <a href="/overlays/testing/namespace.yaml">namespace.yaml</a><br>
	&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <a href="/overlays/testing/testing.env">testing.env</a><br>
<br><br><p>
</body>
</html>
