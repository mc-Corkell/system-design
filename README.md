# Technology Stack Comparison: Meta (Facebook), Industry, and AWS

| **Layer** | **Meta (Facebook)** | **Industry** | **AWS Service** |
| --- | --- | --- | --- |
| **Cloud Platform** | Proprietary, as well as using AWS, Azure, and Google | AWS, Azure, Google Cloud | AWS |
| **Queue / Async Tier** | RabbitMQ, ZeroMQ | RabbitMQ, ZeroMQ | Amazon SQS |
| **Stream** | Kafka, Hive, HBase, Scribe | Apache Kafka, Redis Streams | Amazon Kinesis, Amazon EventBridge |
| **Containerization** | Tupperware (now called Twine) | Docker & Kubernetes | AWS ECS - Elastic Container Service |
| **CI/CD** | Sandcastle, Landcastle | Jenkins, GitHub Actions, GitLab CI/CD | AWS CodePipeline, AWS CodeDeploy |
| **Code Review** | Phabricator (forked) | GitHub, GitLab | – |
| **Version Control** | Sapling (formerly Mercurial Hg), Git | Git | – |
| **OS** | Linux | Linux | Linux |
| **Database** | MySQL, RocksDB, TAO (custom NoSQL FB API) | MySQL, PostgreSQL, MongoDB, DynamoDB | AWS Aurora, AWS DynamoDB, Amazon RDS |
| **Search** | Custom, Elasticsearch | Elasticsearch | AWS OpenSearch |
| **Server-side Programming** | Hack, C++, Haxl, Rust, Python, Java | C++, C#, Java, Python, GoLang, Rust … | Any |
| **Cache** | Memcache | Memcache, Redis, DynamoDB | AWS ElastiCache (supports Redis and Memcached) |
| **Load Balancer** | Proxygen, Katran | Nginx, HAProxy | AWS ELB - Elastic Load Balancing |
| **CDN** | FBCDN, Facebook Edge Network, Akamai | Cloudflare | AWS CloudFront |
| **Mobile Client** | React Native, Swift, Objective-C, Lightspeed, Kotlin, Native Templates | React Native, Swift, Objective-C, Kotlin, Flutter … | Any |
| **Web Client** | React, JavaScript, TypeScript, GraphQL | JavaScript, TypeScript, React, Ruby on Rails, Next.js, Django, Rust … | Any |
| **Security** | OAuth, custom | OAuth, Okta | AWS Cognito, IAM |
