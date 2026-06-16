# Publications

## SPIDER: Two Server Functionality for the Cost of Zero

**Ofir Dvir, Kali Hale, Javin Zipkin, Divyakant Agrawal, Dahlia Malkhi**

Preprint, 2026

[arXiv:2605.21857](https://arxiv.org/abs/2605.21857) | [ePrint:2026/1134](https://eprint.iacr.org/2026/1134)

We introduce baseSPIDER and SPIDER, private information retrieval (PIR) schemes that embody two technical advancements. The baseSPIDER protocol operates with a single server and a stateful client that performs pre-processing and stores hints for future queries. In this setting, baseSPIDER introduces a new approach that matches the asymptotically optimal communication complexity of state-of-the-art schemes while improving constant factors--an advantage that is particularly significant for databases with large entries. In addition, baseSPIDER offers a conceptually simpler design relative to prior protocols. SPIDER operates over a default database interface and requires no cooperation from the server at any stage. To our knowledge, SPIDER is the first single-server PIR construction of this design, achieving privacy without specialized APIs, auxiliary server state, or protocol-specific interaction beyond conventional indexed access. SPIDER is built via a simple transformation of baseSPIDER to the default server setting, eliminating deployment barriers and enabling immediate applicability to existing systems. This transformation can be applied more broadly to three recent PIR solutions, adapting them for use in the default-server paradigm and yielding solutions of independent interest. SPIDER compares to the resulting modified solutions by exhibiting a simpler design while incurring higher client computational work.
