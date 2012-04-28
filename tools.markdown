### Tools

## s3cmd
command line tool to work with (mainly) AWS S3
[http://s3tools.org/s3cmd](http://s3tools.org/s3cmd)

## mPDF
[http://www.mpdf1.com/](http://www.mpdf1.com/)

## BASH
List directories with number of files and total size
<pre>
find /data/sfsspt/scans/ -maxdepth 2 -type d | while read dir 
do      
  count=$(find "$dir"  -type f | wc -l)
  size=$(du -hs "$dir"|awk '{print $1}')
  echo "$dir ; $count : $size"
done
</pre>