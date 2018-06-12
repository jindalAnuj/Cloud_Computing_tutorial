## What is Block Storage
Block storage services are relatively simple and familiar. They provide a traditional block storage device — like a hard drive — over the network. Cloud providers often have products that can provision a block storage device of any size and attach it to your virtual machine.

**Advantages**

- [x] Block storage is a familiar paradigm. People and software understand and support files and filesystems almost universally
- [x] Block devices are well supported. Every programming language can easily read and write files
- [x] Filesystem permissions and access controls are familiar and well-understood
- [x] Block storage devices provide low latency IO, so they are suitable for use by databases. 

**Disadvantages**

- [x] Storage is tied to one server at a time
- [x] Blocks and filesystems have limited metadata about the blobs of information they're storing (creation date, owner, size). Any additional information about what you're storing will have to be handled at the application and database level, which is additional complexity for a developer to worry about
- [x] You need to pay for all the block storage space you've allocated, even if you're not using it
- [x] You can only access block storage through a running server
- [x] No MetaData
- [x] Block storage needs more hands-on work and setup vs object storage (filesystem choices, permissions, versioning, backups, etc.)


## What is Object Storage
Object storage (also referred to as object-based storage) is a general term that refers to the way in which we organize and work with units of storage, called objects.

**Advantages**
- [x] Its Contains Meta Data
- [x] Can scale infinitely to petabytes and beyond.
- [x] Performs best for big content and high stream throughput
- [x] Data can be stored across multiple regions.

**Disvantages**

- [x] Operating systems can't easily mount an object store like a normal disk.
- [x] Object storage doesn't allow you to alter just a piece of a data blob.


[Source](https://www.digitalocean.com/community/tutorials/object-storage-vs-block-storage-services)
