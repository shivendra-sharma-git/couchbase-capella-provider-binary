# couchbase-capella-provider-binary

We created this repo because [capella provider](https://github.com/couchbasecloud/terraform-provider-couchbasecapella) is not published yet so provider can be downloaded from this repo without building. 

To use it execute below commands.

```

# mkdir -p ~/.terraform.d/plugins/
# cd ~/.terraform.d/plugins/
# wget https://github.com/shivendra-sharma-git/couchbase-capella-provider-binary/raw/main/terraform.couchbase.com.zip
# unzip terraform.couchbase.com.zip
Archive:  terraform.couchbase.com.zip
   creating: terraform.couchbase.com/
   creating: terraform.couchbase.com/local/
   creating: terraform.couchbase.com/local/couchbasecapella/
   creating: terraform.couchbase.com/local/couchbasecapella/1.0.0/
   creating: terraform.couchbase.com/local/couchbasecapella/1.0.0/darwin_amd64/
  inflating: terraform.couchbase.com/local/couchbasecapella/1.0.0/darwin_amd64/terraform-provider-couchbasecapella  
# rm -rf terraform.couchbase.com.zip
```

Note: Once its published this repo can be deleted. 
