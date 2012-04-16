### Git

[github](http://github.com)


### Records

[records](http://trac.sharedrecords.org/wiki/HttpApi)

### curl

## PUT a file  

	upload file with PUT, with details 	
		curl --verbose --upload-file original.txt http://url:port/records/file.name
	add headers:
		curl --verbose -H "x-amz-meta-record-file-extension:txt" --upload-file original.txt http://url:port/records/file.name