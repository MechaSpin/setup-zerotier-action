# setup-zerotier-action

This action connects the runner executing the action to a [ZeroTier](https://www.zerotier.com/) network, so it can access resources on that network. 
When the workflow completes, it will leave the ZeroTier network. 

# Usage

```yaml
- uses: mckinleytechnologies/setup-zerotier-action@v1
  with:
    # The ZeroTier Network ID to join.
    network_id: '''
```
