# k8s-cronjob-msteams
Send notifications to an MS Teams webhook using a k8s cronjob

The webhook url is passed to the cronjob as a secret, 

The message that will be posted to the endpoint can be defined as an environment variable on the cronjob container
