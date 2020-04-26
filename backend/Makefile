build:
	GOOS=linux go build -o app
	docker build -t speech/say .
	rm -f app