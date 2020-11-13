VERSION := 1.0.0

build-glci:
	docker build --no-cache --build-arg VERSION=$(VERSION) -f Dockerfile.glci -t doc.ker.dev.dszn.cz/neznam/wagtail-glci:$(VERSION) -t doc.ker.dev.dszn.cz/neznam/wagtail-glci:latest .

push-glci:
	docker push doc.ker.dev.dszn.cz/neznam/wagtail-glci:${VERSION}
	docker push doc.ker.dev.dszn.cz/neznam/wagtail-glci:latest
