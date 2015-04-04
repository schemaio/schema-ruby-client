# Schema API Client for Ruby

Build and scale ecommerce with Schema. Create a free account at https://schema.io

## Example

```ruby
require 'schema'

client = Schema::Client.new({
	"id": "<clientid>",
	"key": "<clientkey>"
))

products = client.get("/categories/shoes/products", {'color': "blue"})

print products.inspect
```

## Documentation

See <http://schema.io/docs/clients#ruby> for more API docs and usage examples

## Contributing

Pull requests are welcome

## License

MIT
