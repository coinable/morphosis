# Morphosis
Morphosis is a metadata resource for Coinable which contains different json and metadata that are fetched for different internal processes or flows.

To add a new collection to Morphosis please use the following structure


```json
{
  "key": "collection_key",
  "image_uri": "image_url_of_the_collection",
}
```

`image_uri` should be consistent, recommended to use one of the NFT pngs via link to `arweave` or any other similar "forever" to exist hosting services. While the image can be just an image generalizing the NFT collection like a custom made 250x250 sized image of multiple NFTs or something that defines the collection. Needs to be unique and not copyrighted in any way.

`key` is the collection key returned from the Metaplex payload.

This JSON structure will probably change in the future.
