# Cloud drivers : s3, hpcloud #

Naturally, with the high rise of the Object-Storage systems, particularly in the cloud, a couple of drivers may help you in getting access to this kind of storage. Currently access.s3 and access.hpcloud are the only ones available.

The access.swift should be generalized to an open-stack Swift driver, as they are actually using this technology. It requires the PHP Swift Bindings.

The S3 driver uses the "Better AS3 Stream Wrapper" class to access the amazon Simple Storage System. You must configure the  API & SECRET KEYS, the REGION to query, and finally the CONTAINER you want to browse. Using this kind of storage driver is handy for cloud architectures, and more features should be developed around it. Worth noting, the "Metastore.S3" is a specific metadata storage implementation that goes along with this driver, using directly the S3 metadata system.

[:image-popup:4_setup_workspaces_and_users/workspaces_object_storages.png]