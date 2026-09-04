### Replicated External IP Addresses

Replicated publishes the current IP addresses that its services listen on, in JSON form, in this repository. These are the addresses that traffic sent to Replicated arrives at, so they are what an online installation connects to.

Replicated does not publish the source IP addresses that its own services use for outbound connections, and does not commit to keeping those addresses stable. Do not use this list to build an allowlist for traffic originating from Replicated.

Any changes to this list will be communicated with at least 30 days notice, when possible. To be notified, use **Watch** on this repository and choose **All Activity**. Starring the repository does not send notifications.

To view the current list, see [ip_addresses.json](./ip_addresses.json).
