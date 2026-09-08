# Disposable release evaluation

This public fixture copies public Backlog Kit source at 6d8bcc45197b42bddb3d60476235a36eb772e033. It is for hosted release validation only. Its package artifacts must not be treated as product releases.

The first CI-only commit tests untagged no-bump behavior. A later approved feature commit exercises v0.1.0 publication through the unchanged organization-owned workflows. No PyPI workflow or credentials are present. Cleanup is a separate decision.
