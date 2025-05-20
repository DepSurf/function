# Function: <code>ZSTD_ldm_fillHashTable</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ZSTD_ldm_fillHashTable(ldmState_t *ldmState, const BYTE *ip, const BYTE *iend, const ldmParams_t *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:240
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff81ea3094-ffffffff81ea30bb: ZSTD_ldm_fillHashTable.cold (STB_LOCAL)
ffffffff81743a80-ffffffff81743c34: ZSTD_ldm_fillHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_ldm_fillHashTable(ldmState_t *ldmState, const BYTE *ip, const BYTE *iend, const ldmParams_t *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:267
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff8208a4c7-ffffffff8208a4ee: ZSTD_ldm_fillHashTable.cold (STB_LOCAL)
ffffffff8185d3a0-ffffffff8185d554: ZSTD_ldm_fillHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_ldm_fillHashTable(ldmState_t *ldmState, const BYTE *ip, const BYTE *iend, const ldmParams_t *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:267
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff8210a91e-ffffffff8210a945: ZSTD_ldm_fillHashTable.cold (STB_LOCAL)
ffffffff8189df60-ffffffff8189e104: ZSTD_ldm_fillHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_ldm_fillHashTable(ldmState_t *ldmState, const BYTE *ip, const BYTE *iend, const ldmParams_t *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:267
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff821e8a8b-ffffffff821e8ab2: ZSTD_ldm_fillHashTable.cold (STB_LOCAL)
ffffffff818efb20-ffffffff818efcc4: ZSTD_ldm_fillHashTable (STB_GLOBAL)
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
