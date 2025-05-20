# Function: <code>crypto_shash_set_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810763bc)
Location: include/crypto/hash.h:714
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/crc32c_generic.c (ffffffff813ab77c)
Location: include/crypto/hash.h:714
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810779bc)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/crc32c_generic.c (ffffffff813eafdc)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107b7ac)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8140460c)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81079f6c)
Location: include/crypto/hash.h:758
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/crc32c_generic.c (ffffffff81411d4c)
Location: include/crypto/hash.h:758
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108065c)
Location: include/crypto/hash.h:766
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff8142c8f3)
Location: include/crypto/hash.h:766
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/crc32c_generic.c (ffffffff8143c4bc)
Location: include/crypto/hash.h:766
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff8144127f)
Location: include/crypto/hash.h:766
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810838a7)
Location: include/crypto/hash.h:765
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff8145f553)
Location: include/crypto/hash.h:765
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/crc32c_generic.c (ffffffff8146f2f7)
Location: include/crypto/hash.h:765
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff8147419f)
Location: include/crypto/hash.h:765
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108a577)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff8147cf83)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8148cca7)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff81491d0f)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e377)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814ab273)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814ba397)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814bf3c0)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108efd7)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814c5f33)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814d3167)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814d83c6)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525584)
Location: include/crypto/hash.h:789
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815424b4)
Location: include/crypto/hash.h:797
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154ab54)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab334)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652b32)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c772)
Location: include/crypto/hash.h:803
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746282)
Location: include/crypto/hash.h:855
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff817888c2)
Location: include/crypto/hash.h:781
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c0f34)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffff8000105cf770)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffff8000105d41f8)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076e860)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (c077d48c)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (c0781cf4)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c00000000074929c)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (c00000000075b7b0)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (c0000000007618d0)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe000405d30)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffe0004146a0)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffe00041852a)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df97)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814be513)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814cb747)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814d09a6)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107caa7)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814aef33)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814bc167)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814c13c6)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df47)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814ba5a3)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814c77d7)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814cca36)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81090327)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In crypto/shash.c (ffffffff814d3053)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814e02a7)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814e5506)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
</ul>

## Differences
