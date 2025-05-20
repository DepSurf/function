# Function: <code>FSE_readNCount_bmi2</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount_bmi2(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81709cc5)
Location: lib/zstd/common/entropy_common.c:223
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
```
**Symbols:**

```
ffffffff8170a020-ffffffff8170a060: FSE_readNCount_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount_bmi2(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818847b5)
Location: lib/zstd/common/entropy_common.c:223
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
```
**Symbols:**

```
ffffffff81884b80-ffffffff81884bc0: FSE_readNCount_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount_bmi2(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818c6cc5)
Location: lib/zstd/common/entropy_common.c:223
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
```
**Symbols:**

```
ffffffff818c7090-ffffffff818c70d0: FSE_readNCount_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_readNCount_bmi2(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81918885)
Location: lib/zstd/common/entropy_common.c:223
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
```
**Symbols:**

```
ffffffff81918c50-ffffffff81918c90: FSE_readNCount_bmi2 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
