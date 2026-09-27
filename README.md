# pipeline-proof-boundaries

## [Define the artifact](./001.md)

> “Provenance refers to verifiable information that can be used to track
> an artifact back [...] to where it came from.”
>
> — SLSA, Provenance v1.2

## [Artifact immutability](./002.md)

> “Higher levels provide increasing protection against tampering of the build,
> the provenance, or the artifact.”
>
> — SLSA, Build Track v1.2

## [Unique and unambiguous artifact identity](./003.md)

> “Finally, the build process outputs one or more artifacts,
> identified by `subject`.”
>
> — SLSA, Build Provenance v1.2

## [Stable resource identity](./004.md)

> “Bicep files are idempotent, which means that you can deploy the same file
> many times and get the same resource types in the same state.”
>
> — Microsoft Learn, Bicep

## [Blocking controls](./005.md)

> “By default, a job runs if it doesn't depend on any other job,
> or if all of the jobs that it depends on completed successfully.”
>
> — Microsoft Learn, Azure Pipelines conditions