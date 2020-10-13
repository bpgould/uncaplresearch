# uncaplresearch
1) This static website it hosted in Amazon S3 with routing handled by Amazon Route 53.
2) I utilized Amazon CloudFront to redirect HTTP->HTTPS and to use a SSL/TLS certificate for security and SEO reasons.
3) I connected Amazon CodePipeline to my GitHub repo and set the CloudFront default root object to index.html.