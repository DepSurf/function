# Function: <code>FSE_buildDTable_wksp</code>

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
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff814b9500)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff814b9500-ffffffff814b9696: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff814ebd70)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff814ebd70-ffffffff814ebf1f: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff814ffac0)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff814ffac0-ffffffff814ffc6f: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff8152dc70)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff8152dc70-ffffffff8152de1f: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff8154eb00)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff8154eb00-ffffffff8154ecaf: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815cca70)
Location: lib/zstd/fse_decompress.c:95
Inline: False
Direct callers:
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
ffffffff815cca70-ffffffff815ccbff: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815ea5f0)
Location: lib/zstd/fse_decompress.c:88
Inline: False
Direct callers:
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
ffffffff815ea5f0-ffffffff815ea786: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815d8700)
Location: lib/zstd/fse_decompress.c:88
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
ffffffff815d8700-ffffffff815d8897: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/fse_decompress.c:88
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
ffffffff81cdd450-ffffffff81cdd4d0: FSE_buildDTable_wksp.cold (STB_LOCAL)
ffffffff816439b0-ffffffff81643b6e: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff8170c3c0)
Location: lib/zstd/common/fse_decompress.c:176
Inline: False
```
**Symbols:**

```
ffffffff8170c3c0-ffffffff8170c3e2: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff81886b20)
Location: lib/zstd/common/fse_decompress.c:176
Inline: False
```
**Symbols:**

```
ffffffff81886b20-ffffffff81886b42: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff818c8f40)
Location: lib/zstd/common/fse_decompress.c:176
Inline: False
```
**Symbols:**

```
ffffffff818c8f40-ffffffff818c8f62: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff8191ab00)
Location: lib/zstd/common/fse_decompress.c:176
Inline: False
```
**Symbols:**

```
ffffffff8191ab00-ffffffff8191ab22: FSE_buildDTable_wksp (STB_GLOBAL)
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
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffff80001065ac48)
Location: lib/zstd/fse_decompress.c:95
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
ffff80001065ac48-ffff80001065adec: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (c08041f8)
Location: lib/zstd/fse_decompress.c:95
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
c08041f8-c08043d4: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (c00000000080bc30)
Location: lib/zstd/fse_decompress.c:95
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
c00000000080bc30-c00000000080be94: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffe000488660)
Location: lib/zstd/fse_decompress.c:95
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
ffffffe000488660-ffffffe00048882c: FSE_buildDTable_wksp (STB_GLOBAL)
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
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815470e0)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff815470e0-ffffffff8154728f: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815373c0)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff815373c0-ffffffff8153756f: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff81542e20)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff81542e20-ffffffff81542fcf: FSE_buildDTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t FSE_buildDTable_wksp(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff8155cc50)
Location: lib/zstd/fse_decompress.c:95
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
ffffffff8155cc50-ffffffff8155cdff: FSE_buildDTable_wksp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>size_t wkspSize</code>
</li>
<li>
<b>Param removed. </b>
<code>void *workspace</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t workspaceSize</code>
</li>
</ul>
</details>
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
