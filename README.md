# HLD (High level system design)

Netflix System Design | YouTube System Design | System Design Interview Question

**1. Adaptive bitrate streaming** - Automaticaly adjust the qualitity of video based upon bandwidth availablity.
2. Large file can be uploaded using SFTP or FTP via production houses.




**Content processor **

  1. File Chunker
  2. Content filter(piracy, legal, nudity etc)
  3. Content tagger (category, classifier, thumbanails etc)
  4. Different Transcodes -> formates(MP4, MPEG, MKV etc)
  5. Quality Converter
  6. CDN Uploads 


**Asset Onboarding Service**

  1.take the file from Production House or User's Mobile device and upload it to S3.
  
  
