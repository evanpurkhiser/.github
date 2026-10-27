# Repository overrides

Add a YAML file named after a repository only when it needs to differ from the
shared policy. Safe Settings overlays repository configuration on the matching
settings from `settings.yml` and `suborgs/`.

Each file uses the Safe Settings
[repository schema](https://github.com/github-community-projects/safe-settings/blob/3.0.0/schema/dereferenced/repos.json).
