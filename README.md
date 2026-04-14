# Reference Graphs

This directory holds `.cgr` files that are useful as operational recipes or syntax illustrations, but are not part of the root feature-exercise validation set.

## What stays at the repo root

The root keeps the graphs that materially exercise CommandGraph behavior and are validated in docs/tests:

- `build.cgr`
- `parallel_test.cgr`
- `multinode_test.cgr`
- `nginx_setup.cgr`
- `webserver.cgr`
- `system_audit.cgr`
- `api_integration.cgr`

## What lives here

The `.cgr` files in this directory are kept as reference material for separate publishing or migration work. Treat the directory contents as the source of truth for which reference graphs are currently available here.

## Syntax authority

Do not duplicate syntax rules in this folder. Use the main project docs as the source of truth:

- GitHub repo: <https://github.com/commandgraph/cgr/>
- Syntax manual: <https://github.com/commandgraph/cgr/blob/main/MANUAL.md>
- Formal spec: <https://github.com/commandgraph/cgr/blob/main/COMMANDGRAPH_SPEC.md>
- Overview and examples: <https://github.com/commandgraph/cgr/blob/main/README.md>

If one of these reference graphs is moved to another repository later, keep links to the upstream docs instead of copying syntax descriptions into that repository.
