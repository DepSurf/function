# Function: <code>xxh64</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8149f3a0)
Location: lib/xxhash.c:172
Inline: False
```
**Symbols:**

```
ffffffff8149f3a0-ffffffff8149f605: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814d45a0)
Location: lib/xxhash.c:172
Inline: False
```
**Symbols:**

```
ffffffff814d45a0-ffffffff814d480b: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814e8ff0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff814e8ff0-ffffffff814e925b: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81515be0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff81515be0-ffffffff81515e95: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81536620)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff81536620-ffffffff815368d5: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8159aba0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff8159aba0-ffffffff8159ae4e: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815b6590)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff815b6590-ffffffff815b683e: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815c13f0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff815c13f0-ffffffff815c169b: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81629260)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff81629260-ffffffff8162950b: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff816fa440)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_fillHashTable
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DDictHashSet_emplaceDDict
```
**Symbols:**

```
ffffffff816fa440-ffffffff816fa708: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff817ecea0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_fillHashTable
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DDictHashSet_emplaceDDict
```
**Symbols:**

```
ffffffff817ecea0-ffffffff817ed168: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8182d100)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_fillHashTable
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DDictHashSet_emplaceDDict
```
**Symbols:**

```
ffffffff8182d100-ffffffff8182d3c8: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8187ec90)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_fillHashTable
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DDictHashSet_emplaceDDict
```
**Symbols:**

```
ffffffff8187ec90-ffffffff8187ef58: xxh64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffff800010643098)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffff800010643098-ffff800010643354: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c07e8b28)
Location: lib/xxhash.c:172
Inline: False
```
**Symbols:**

```
c07e8b28-c07e9310: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c0000000007ee400)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
c0000000007ee400-c0000000007ee790: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffe00046f4f4)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffe00046f4f4-ffffffe00046f980: xxh64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152ec00)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff8152ec00-ffffffff8152eeb5: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8151eee0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff8151eee0-ffffffff8151f195: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152a940)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff8152a940-ffffffff8152abf5: xxh64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
uint64_t xxh64(const void *input, const size_t len, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815446a0)
Location: lib/xxhash.c:172
Inline: False
Direct callers:
  - mm/ksm.c:calc_checksum
```
**Symbols:**

```
ffffffff815446a0-ffffffff81544955: xxh64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
