# Working on this site

Work directly on `main`; do not create feature branches. Move fixes promptly through independent review where applicable, then run the applicable checks and tests and whatever smoke test or validation you judge necessary. Push the change to `main` to publish it on the live site without a separate release approval from the maintainer. This direct-to-main, validated publishing flow is the intended way to develop this site. If a bug turns up after publishing, the maintainer files a bug report.

For large features, land useful increments on `main` behind a disabled feature flag until the feature is ready to enable.

After publishing, verify the served GitHub Pages build and the affected pages.
