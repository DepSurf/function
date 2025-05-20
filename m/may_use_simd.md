# Function: <code>may_use_simd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e5ad)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108f20d)
Location: arch/x86/include/asm/simd.h:9
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810954e1)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109471e)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109508e)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810a502e)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff810b9fc0)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810ba186)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff810d5d10)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810d5f26)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e0a0c)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810e1250)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e1466)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e928c)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810e9ad0)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e9ce6)
Location: arch/x86/include/asm/simd.h:9
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff80001008869c)
Location: arch/arm64/include/asm/simd.h:26
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e1cd)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107ccdd)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e17d)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109055d)
Location: arch/x86/include/asm/simd.h:9
Inline: True
```
</details>
</li>
</ul>

## Differences
