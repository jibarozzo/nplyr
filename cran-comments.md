## Resubmission

This is a resubmission. In this version I have:

* Updated all repository URLs in README.md to point to the new repository location (jibarozzo/nplyr)
* Fixed the package maintainer information in DESCRIPTION, transferring maintainership from Mark Rieke to Bolívar Aponte Rolón
* Resolved previous Rd cross-reference issues with missing package anchors in nest_fill.Rd
* Incremented the version number from 0.2.0.9000 to 0.3.0 to reflect the maintainer change and fixes

## R CMD check results

0 errors | 0 warnings | 0 notes

## Gains new maintainer

The package has been transferred to a new maintainer. From Mark Rieke (markjrieke@gmail.com) to Bolívar Aponte Rolón (bolaponte@pm.me). The DESCRIPTION file has been updated accordingly, with Mark Rieke now listed as an author ("aut") and Bolívar Aponte Rolón as the maintainer ("cre").

## Resolved previous check failures

The previous check failure from 2025-05-28 regarding Rd cross-references has been resolved:

```
Check: Rd cross-references
Result: NOTE 
  Found the following Rd file(s) with Rd \link{} targets missing package
  anchors:
    nest_fill.Rd: tidyr_tidy_select
  Please provide package anchors for all Rd \link{} targets not in the
  package itself and the base packages.
```

This issue has been fixed, as confirmed by our local check:
```
> devtools::check_man()
ℹ Updating nplyr documentation
ℹ Loading nplyr
ℹ Checking documentation...
✔ No issues detected
```

Thank you for your consideration.