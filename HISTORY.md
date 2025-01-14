# History

## v6.0.0 2021 August 1

-   Thanks to [Kukhyeon Heo](https://github.com/sainthkh) for [pull request #214](https://github.com/bevry/istextorbinary/pull/214) `istextorbinary` can now speak UTF8 multibyte characters, now understanding that Crilly, CJK, Emoji, etc. are not binary. This is a big win.
    -   Closes [issue #13](https://github.com/bevry/istextorbinary/issues/13) reported by [dlsgusrn7577](https://github.com/dlsgusrn7577)
-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.15.0 2021 July 30

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.14.0 2021 July 29

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.13.0 2021 July 28

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.12.0 2020 October 29

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.11.0 2020 September 5

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.10.0 2020 August 18

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.9.0 2020 August 4

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.8.0 2020 July 22

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.7.0 2020 June 25

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.6.0 2020 June 21

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.5.0 2020 June 21

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.4.0 2020 June 21

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.3.0 2020 June 20

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.2.0 2020 June 10

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.1.0 2020 June 10

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v5.0.0 2020 May 30

-   Potential Breaking Change: Removed the long-standing deprecated sync, callback, and promise wrappers, now the only exports are `isText`, `isBinary`, and `getEncoding`
-   Potential Breaking Change: `getEncoding` now checks start, middle, and end if `checkBegin` was not provided. Prior functionality only checked start, middle, and end, if `opts` were not provided. This new functionality allows custom `checkLength` for start, middle, and end.
-   Converted to TypeScript, and provided proper documentation for `isBinary` instead of just referencing `isText`, so your intellisense is now more helpful
-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v4.3.0 2020 May 22

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v4.2.0 2020 May 21

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v4.1.0 2020 May 21

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v4.0.0 2020 May 11

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)
-   Minimum required node version changed from `node: >=8` to `node: >=10` to keep up with mandatory ecosystem changes

## v3.3.0 2019 December 9

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v3.2.0 2019 December 1

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v3.1.0 2019 December 1

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v3.0.0 2019 November 18

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)
-   Minimum required node version changed from `node: >=0.12` to `node: >=8` to keep up with mandatory ecosystem changes

## v2.6.0 2019 November 13

-   Updated dependencies, [base files](https://github.com/bevry/base), and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v2.5.1 2019 January 21

-   Fixed a readme documentation inconsistency

-   Fixed node v0.12 and v4 support (regression since v2.5.0)

## v2.5.0 2019 January 21

As the detection algorithms are result returns, with the asynchronous signatures just wrappers, we have changed `isText`, `isBinary`, and `getEncoding` to return the result if no callback was provided to them, maintaining backwards compatibility, but encouraging intuitive usage of the methods with the least overhead.

-   The following methods have had return signatures added to them, which should be the preferable usage:

    -   `isText`, which you should use instead of `isTextSync` (a method which only lingers for backwards compatibility)
    -   `isBinary`, which you should use instead of `isBinarySync` (a method which only lingers for backwards compatibility)
    -   `getEncoding`, which you should use instead of `getEncoding` (a method which only lingers for backwards compatibility)

-   If you require callback usage, the following callback wrapper methods have been added:

    -   `isTextCallback`, which you should use instead of `isText`'s callback signature (a signature which only lingers for backwards compatibility)
    -   `isBinaryCallback`, which you should use instead of `isBinary`'s callback signature (a signature which only lingers for backwards compatibility)
    -   `getEncodingCallback`, which you should use instead of `getEncoding`'s callback signature (a signature which only lingers for backwards compatibility)

-   If you require promise usage, the following promise wrapper methods have been added:

    -   `isTextPromise` which wraps `isText` with a promise signature
    -   `isBinaryPromise` which wraps `isBinary` with a promise signature
    -   `getEncodingPromise` which wraps `getEncoding` with a promise signature

-   `isBinary` method now correctly returns `null` instead of `true` when no inputs are provided

-   Added tests for all methods

## v2.4.2 2019 January 21

-   Added more keywords to `package.json`

## v2.4.1 2019 January 21

-   README now elaborates on the operation of this package

## v2.4.0 2019 January 20

-   Asynchronous methods now `try...catch` the synchronous methods to ensure an error from invalid inputs would be given to the callback.
    -   Before they would not do any `try...catch` so if invalid inputs were given, the error would throw.
-   The JSDoc documentation has been updated for accuracy.
    -   It previously indicated that the return types of the sync methods could have been an error instance, this was incorrect, they would throw if received invalid inputs.
    -   It previously indicated that the result for of the async `getEncoding` callback was a boolean, this was incorrect, it would be the string result of `getEncodingSync`.
-   Updated [base files](https://github.com/bevry/base) and [editions](https://editions.bevry.me) using [boundation](https://github.com/bevry/boundation)

## v2.3.0 2018 November 7

-   Ensure that [textextensions](https://github.com/bevry/textextensions) and [binaryextensions](https://github.com/bevry/binaryextensions) are the latest versions at the time of publishing
-   Updated [base files](https://github.com/bevry/base) and [editions](https://github.com/bevry/editions) using [boundation](https://github.com/bevry/boundation)

## v2.2.1 2018 January 24

-   Added missing development dependency

## v2.2.0 2018 January 24

-   Fixed invalid `package.json` error
    -   Thanks to [Sean](https://github.com/AlbinoDrought) for [pull request #8](https://github.com/bevry/istextorbinary/pull/8)
-   Updated base files

## v2.1.0 2016 May 10

-   Support v2 of [textextensions](https://github.com/bevry/textextensions) and [binaryextensions](https://github.com/bevry/binaryextensions)

## v2.0.0 2016 May 2

-   Converted from CoffeeScript to JavaScript
-   Fixed `getEncoding` and `isText` not handling errors correctly
-   Right-most extension takes preference, instead of left-most
    -   Thanks to [Ian Sibner](https://github.com/sibnerian) for [pull request #5](https://github.com/bevry/istextorbinary/pull/5)
    -   **This has bumped the major** as it changes the output result, which could potentially break some apps, despite the API remaining exactly the same

## v1.0.2 2015 January 16

-   Fixed build
-   Added test for text files

## v1.0.1 2015 January 16

-   Cleaned up thanks to [Shunnosuke Watanabe](https://github.com/shinnn) for [pull request #2](https://github.com/bevry/istextorbinary/pull/2)

## v1.0.0 2013 October 25

-   Initial release [extracted](https://github.com/balupton/bal-util/blob/6501d51bc0244fce3781fc0150136f7493099237/src/lib/paths.coffee#L100-L201) from [bal-util](https://npmjs.com/package/bal-util) where it was introduced [2012 September 24](https://github.com/balupton/bal-util/blob/master/HISTORY.md#v1137-2012-september-24).
