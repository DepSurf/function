# Function: <code>FSE_readNCount</code>

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
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814b90b0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff814b90b0-ffffffff814b932c: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814eb8c0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff814eb8c0-ffffffff814ebb78: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814ff610)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff814ff610-ffffffff814ff8c8: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8152d7d0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff8152d7d0-ffffffff8152da89: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8154e660)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff8154e660-ffffffff8154e919: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815cc580)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff815cc580-ffffffff815cc878: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815ea100)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff815ea100-ffffffff815ea3ff: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815d8210)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff815d8210-ffffffff815d8509: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/entropy_common.c (0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81cdd3d0-ffffffff81cdd412: FSE_readNCount.cold (STB_LOCAL)
ffffffff816434c0-ffffffff81643793: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81709cc5)
Location: lib/zstd/common/entropy_common.c:236
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff8170a060-ffffffff8170a07f: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818847b5)
Location: lib/zstd/common/entropy_common.c:236
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff81884bd0-ffffffff81884bef: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818c6cc5)
Location: lib/zstd/common/entropy_common.c:236
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff818c70e0-ffffffff818c70ff: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81918885)
Location: lib/zstd/common/entropy_common.c:236
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff81918ca0-ffffffff81918cbf: FSE_readNCount (STB_GLOBAL)
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
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffff80001065a780)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffff80001065a780-ffff80001065aa6c: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (c0803d78)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
c0803d78-c080402c: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (c00000000080b5a8)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
c00000000080b5a8-c00000000080b994: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffe0004881b0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffe0004881b0-ffffffe00048849a: FSE_readNCount (STB_GLOBAL)
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
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff81546c40)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81546c40-ffffffff81546ef9: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff81536f20)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81536f20-ffffffff815371d9: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff81542980)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81542980-ffffffff81542c39: FSE_readNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t FSE_readNCount(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8155c7b0)
Location: lib/zstd/entropy_common.c:59
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff8155c7b0-ffffffff8155ca69: FSE_readNCount (STB_GLOBAL)
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
