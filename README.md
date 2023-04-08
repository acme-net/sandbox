# The AcmeNet Sandbox

The Acmenet sandbox is a test network that anyone can join and subscribe and test their implementations. Subscribing to this Sandbox is important if,

1. You wish to join Acmenet as a live participant
2. You wish to upgrade your existing AcmeNet implementation
3. You want to create rich integrated multi-domain experiences

# The AcmeNet Sandbox Registry

To join the AcmeNet sandbox, one must be added to the AcmeNet sandbox registry. The AcmeNet sandbox registry is maintained by the AcmeNet Corporation. 

# Terms and Conditions

- Joining the AcmeNet sandbox is **ABSOLUTELY FREE**. 
- However, participants joining the AcmeNet sandbox must adhere to the [Open AcmeNet Community Guidelines](sandbox-guidelines.md)
- Any participant that violates the open community guidelines shall be removed from the registry

# Joining the AcmeNet Sandbox

Joining the AcmeNet Sandbox consists of the following steps

## Step 1: Create subscriber entry
1. Clone this repository
2. Checkout the `join` branch
3. Create a new branch that has the same name as your fully qualified domain name. For example if your FQDN is "example.com", then your branch name should be `example.com`. Please do not include subdomains. 
4. Add your entry at the bottom of the `subscribers.json` file. To know more about how to construct your entry, click [here](#)
5. Save and commit your file with the message "subscribe"

## Step 2: Submit PR
1. Create a PR to the `join` branch with the updated `subscriber.json` file
2. In case your PR has merge conflicts, please resolve those conflicts and re-submit your PR
3. Wait for your PR to be approved

If your details have been verified by the community of participants or the AcmeNet administrator, you should find your entry in the subscribers.json file.

Please allow atleast 24 hours for the community to verify your subscription details. In case you need urgent assistance, please send an email to the AcmeNet administrator - admin.acmenet@acmecorp.org
