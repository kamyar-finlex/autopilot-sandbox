# How Autopilot works

This is how a ticket travels from Linear to the live site:

1. **Delegated in Linear.** Someone delegates the ticket to Autopilot in Linear.
2. **Planned and implemented.** Autopilot plans the change and implements it on its own branch.
3. **Pull request and CI.** Autopilot opens a pull request, and CI runs its checks.
4. **AI review and merge.** Autopilot's AI review approves the change, and Autopilot merges it.
5. **Redeploy and browser check.** The site redeploys, and Autopilot checks the page in a browser before closing the ticket.
