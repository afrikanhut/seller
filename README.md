# seller
Multi seller, multi vendor e-commerce marketplace with focus on maximal minimalism.

![logo.png](logo.png)

## Theory of Operation

- All CC processing via 3rd party, no valuable information on server.
- Shocking support for multiple domains, as they become the prime mover.
- Simply point a domain at the IP, and get a store.
- Plugin support (ex. seller-widgets, seller-things, seller-products)

## Previous Research

1. seller is based on core concepts behind https://github.com/fantasyui-com/online-marketplace but it focuses on automation over convention, whereas online marketplace keeps its focus on convention over configuration.
2. seller has a server stack designed to wrap it in a hands free CentOS: https://github.com/fantasyui-com/linode-nodejs
3. seller is to be used with external DNS, simply aim the A record at the IP Address.
