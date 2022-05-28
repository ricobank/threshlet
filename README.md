# Threshlet

Threshlet is a simple standard for implementing DAOs and DONs using
[EC threshold signatures](https://x.mypinata.cloud/ipfs/QmNhemU9oZ1HrWBapP2zQsTVhS4HXG3MAZV4mV4dsYnmk3).

It can be thought of a way of bringing business logic to web3
which might not be as decentralized as a full blown POW or POS system,
but is still dramatically more decentralized and auditable than
their analagous web2 systems.

It uses the [streamlet](https://x.mypinata.cloud/ipfs/QmPdzor1xQ76XXb1RpWBu4s1TVZ4TshSBhiRWS1ZBwRfhM)
consensus protocol as its core.
2/3 tsig can rotate members; the rules for doing so are
outside the scope of this standard and can be defined using contracts on Ethereum or any other platform.

A threshchain is a chain of messages with the following form:

    ...

The signature mask to verify looks like this:

    ...

where `unique` is some kind of unique identifier to distinguish this threshlet for signing purposes.