# Function: <code>ZSTD_createDDict_advanced</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b1cdd)
Location: lib/zstd/decompress.c:2039
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e6879)
Location: lib/zstd/decompress.c:2039
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fa229)
Location: lib/zstd/decompress.c:2039
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152789a)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff8154872a)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff815d43ca)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff815f204f)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff815d3b6f)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff8163e8bf)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DDict *ZSTD_createDDict_advanced(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff817508f3)
Location: lib/zstd/decompress/zstd_ddict.c:142
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff81750760-ffffffff8175081d: ZSTD_createDDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DDict *ZSTD_createDDict_advanced(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81874ab3)
Location: lib/zstd/decompress/zstd_ddict.c:142
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff81874900-ffffffff818749bd: ZSTD_createDDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DDict *ZSTD_createDDict_advanced(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff818b5813)
Location: lib/zstd/decompress/zstd_ddict.c:142
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff818b5660-ffffffff818b571d: ZSTD_createDDict_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DDict *ZSTD_createDDict_advanced(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff819073d3)
Location: lib/zstd/decompress/zstd_ddict.c:142
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff81907220-ffffffff819072dd: ZSTD_createDDict_advanced (STB_GLOBAL)
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
In lib/zstd/decompress.c (ffff8000106546bc)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c07ff9f4)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000803fd8)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000481fd2)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
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
In lib/zstd/decompress.c (ffffffff81540d0a)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff81530fea)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff8153ca4a)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
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
In lib/zstd/decompress.c (ffffffff8155687a)
Location: lib/zstd/decompress.c:2040
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDDict
```
</details>
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
