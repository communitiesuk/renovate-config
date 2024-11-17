# Shared renovate config (ostensibly for the Funding Service)

This repository stores config for Renovate (a dependabot alternative) so that it doesn't have to be declared duplicatively across multiple repositories, as it's likely we'll want to have the same (or very similar) rules everywhere.

For any repos that _do_ want specific rules, they can still extend the rules in their own `renovate.json` file.
