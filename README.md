# Hyperscan

Hyperscan is a high-performance multiple regex matching library. It follows the
regular expression syntax of the commonly-used libpcre library, but is a
standalone library with its own C API.

Hyperscan uses hybrid automata techniques to allow simultaneous matching of
large numbers (up to tens of thousands) of regular expressions and for the
matching of regular expressions across streams of data.

Hyperscan is typically used in a DPI library stack.

# Documentation

Information on building the Hyperscan library and using its API is available in
the [Developer Reference Guide](http://intel.github.io/hyperscan/dev-reference/).

# License

Hyperscan is licensed under the BSD License. See the LICENSE file in the
project repository.

# Versioning

The `master` branch on Github/kunpengcompute will always contain the most recent 
release of Intel Hyperscan. 

The `aarch64` branch on Github/kunpengcompute will always contain the most recent 
release that supports the AArch64 architecture. The AArch64 branch was developed
based on Intel Hyperscan 5.4.2. Each version released to `aarch64` branch goes through
QA and testing before it is released; if you're a user of AArch64, rather than a developer,
this is the version you should be using.

# Porting
Perform platform-specific operations, including compilation, 
detecting specific header files, SIMD instruction judgment, and so on.

# Optimization
Improve the Kunpeng platform by using the NEON instructions, inline assembly, 
data alignment, instruction alignment, memory data prefetching, static branch 
prediction, code structure optimization, etc.

# Get Involved

The official homepage for Hyperscan is at [www.hyperscan.io](https://www.hyperscan.io).

`master` branch

If you have questions or comments, we encourage you to [join the mailing
list](https://lists.01.org/mailman/listinfo/hyperscan). Bugs can be filed by
sending email to the list, or by creating an issue on Github.

If you wish to contact the Hyperscan team at Intel directly, without posting
publicly to the mailing list, send email to
[hyperscan@intel.com](mailto:hyperscan@intel.com).

`aarch64` branch

If you have questions or comments, we encourage you to create an issue on Github.

If you wish to contact the Huawei team directly, you can send an email to 
kunpengcompute@huawei.com.
