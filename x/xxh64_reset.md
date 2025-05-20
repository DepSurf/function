# Function: <code>xxh64_reset</code>

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
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8149fde0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff8149fde0-ffffffff8149fe95: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814d4fa0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff814d4fa0-ffffffff814d5055: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814e99f0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff814e99f0-ffffffff814e9aa5: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81516630)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff81516630-ffffffff815166e5: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81537070)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff81537070-ffffffff81537125: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8159b5d0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_resetCCtx_advanced
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff8159b5d0-ffffffff8159b685: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815b6fc0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_resetCCtx_advanced
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815b6fc0-ffffffff815b7075: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815c1e30)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815c1e30-ffffffff815c1ee5: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81629ca0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81629ca0-ffffffff81629d55: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff816faf50)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff816faf50-ffffffff816fb016: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff817edab0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff817edab0-ffffffff817edb76: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8182dec0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff8182dec0-ffffffff8182df86: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8187fa50)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff8187fa50-ffffffff8187fb16: xxh64_reset (STB_GLOBAL)
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
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffff800010643b50)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffff800010643b50-ffff800010643bf8: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c07ea230)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
c07ea230-c07ea308: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c0000000007ef240)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
c0000000007ef240-c0000000007ef324: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffe000470572)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffe000470572-ffffffe0004705da: xxh64_reset (STB_GLOBAL)
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
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152f650)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff8152f650-ffffffff8152f705: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8151f930)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff8151f930-ffffffff8151f9e5: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152b390)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff8152b390-ffffffff8152b445: xxh64_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xxh64_reset(struct xxh64_state *statePtr, const uint64_t seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815450f0)
Location: lib/xxhash.c:256
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff815450f0-ffffffff815451a5: xxh64_reset (STB_GLOBAL)
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
