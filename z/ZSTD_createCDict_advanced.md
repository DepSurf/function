# Function: <code>ZSTD_createCDict_advanced</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, unsigned int byReference, ZSTD_parameters params, ZSTD_customMem customMem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b93ed)
Location: lib/zstd/compress.c:2847
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815b8fc0-ffffffff815b9335: ZSTD_createCDict_advanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, unsigned int byReference, ZSTD_parameters params, ZSTD_customMem customMem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d68d2)
Location: lib/zstd/compress.c:2847
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815d64a0-ffffffff815d681a: ZSTD_createCDict_advanced (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_compressionParameters cParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171aff0)
Location: lib/zstd/compress/zstd_compress.c:3672
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
```
**Symbols:**

```
ffffffff8171aff0-ffffffff8171b0ac: ZSTD_createCDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_compressionParameters cParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818107d0)
Location: lib/zstd/compress/zstd_compress.c:4758
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
```
**Symbols:**

```
ffffffff818107d0-ffffffff8181088c: ZSTD_createCDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_compressionParameters cParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818512b0)
Location: lib/zstd/compress/zstd_compress.c:4758
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
```
**Symbols:**

```
ffffffff818512b0-ffffffff8185136c: ZSTD_createCDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced(const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_compressionParameters cParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a2e70)
Location: lib/zstd/compress/zstd_compress.c:4758
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
```
**Symbols:**

```
ffffffff818a2e70-ffffffff818a2f2c: ZSTD_createCDict_advanced (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
