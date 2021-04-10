pf:
	kc port-forward svc/argocd-server -n argocd 8080:443

getpw:
	kcg pods -n argocd -l app.kubernetes.io/name=argocd-server -o name | cut -d'/' -f 2