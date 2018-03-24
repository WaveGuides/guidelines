# AWG Semantic Versioning

Following the guides from [SemVer](https://semver.org) we intend to have a similar setup for both the hardware and software. This makes it possible to check if a firmware version is compatible with a PCB revision.

## How
Given a version number `MAJOR.MINOR.PATCH`, increment the:

  * `MAJOR` when we make a incompatible hardware-software change
  * `MINOR` when we add functionality in a backwards-compatible manner
  * `PATCH` when we make backwards-compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions to the `MAJOR.MINOR.PATCH` format.

For example, say you have a version `1.0.0` candidate ready but want to test it before you make your release. You could label the pre-release versions as follows:

    1.0.0-alpha.1
    1.0.0-alpha.2

Once you are happy with the stability of `1.0.0`, you can make the official release and drop the `alpha.x` label.

## Where to start?

  1. Start with version `0.1.0`
  2. Make as many breaking changes as needed 
  3. Realease version `1.0.0` to the public
  4. Increment version as [described above](#How)

## Notes
Version numbers should not be confused with bach numbers. We track batch numbers from original equipment manufacturer in `oem_batch.csv` you can find inside the projects repository.
