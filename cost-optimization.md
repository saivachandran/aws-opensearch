# four keys to lower cost for opensearch service
   - shard strategy
   - latest geneartion gravitan2 instances EBS GP3 volumes
   - opensearch serverless
   - storage tier
# shard strategy
  - index composed of shards
  - primary shards
  - replica shards

# shard size is important
 - 10 to 30 Gb for searches
 - 30 to 50 GB for logs (time series data)
 - maximum size dos not exceed 50 GB

# gravita2 instances
 - 38% improvements indexing througput
 - 50 % reduction in index latency
 - 40 % improements on query performance
 - 10 % lower prize on instance prize

# EBS GP3 volumes
  - 9.3 % lower cost EBS GP2 volumes

# storage tire
  - sent data to amazon opensearch service use ism (index management service) for automatic migration and deletion
  - data indexed and stored in hot tier
  - migrate index to ultrawarm staorage
  - once data not require for search move data to cold storage
  


   
    
