# JitIlVerification: Conservatory Edition

For the original repository, please visit https://github.com/DouglasDwyer/JitIlVerification

## Changes

JitIlverification: Conservatory Edition implements some special behavior specifically designed for [The Conservatory](https://xansworkshop.com/conservatory). The behavioral changes include the following:

1. Verifier now has a boolean value which can cause it to ignore pointer loads/stores and localloc (typically these are marked as unverifiable).
2. Verifier now has a boolean value which can cause it to ignore only localloc (typically this is marked as unverifiable).