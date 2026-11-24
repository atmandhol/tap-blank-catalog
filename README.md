# Blank Tap Catalog

TAP or Tanzu Application Platform has a GUI. This catalog is required to install TAP GUI during TAP installation.

It contains the TAP GUI component, system, domain and default groups, and registers the sample apps of the
[Application Accelerator samples](https://github.com/vmware-tanzu/application-accelerator-samples), pinned to the
`tap-1.12.6` tag so the catalog does not change under TAP GUI when `main` moves.

To move to a newer TAP release, replace `tap-1.12.6` in `catalog-info.yaml` with the matching tag from the samples repository
(for example `tap-1.13.0`) and check that every sample's `catalog/catalog-info.yaml` still exists at that tag.
