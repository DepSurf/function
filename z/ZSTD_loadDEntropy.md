# Function: <code>ZSTD_loadDEntropy</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_loadDEntropy(ZSTD_entropyDTables_t *entropy, const const void * dict, const size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff817529d0)
Location: lib/zstd/decompress/zstd_decompress.c:1222
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
**Symbols:**

```
ffffffff817529d0-ffffffff81752d62: ZSTD_loadDEntropy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_loadDEntropy(ZSTD_entropyDTables_t *entropy, const const void * dict, const size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81876ea0)
Location: lib/zstd/decompress/zstd_decompress.c:1268
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
**Symbols:**

```
ffffffff81876ea0-ffffffff81877232: ZSTD_loadDEntropy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_loadDEntropy(ZSTD_entropyDTables_t *entropy, const const void * dict, const size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b7c50)
Location: lib/zstd/decompress/zstd_decompress.c:1287
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
**Symbols:**

```
ffffffff818b7c50-ffffffff818b7fe2: ZSTD_loadDEntropy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_loadDEntropy(ZSTD_entropyDTables_t *entropy, const const void * dict, const size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81909810)
Location: lib/zstd/decompress/zstd_decompress.c:1287
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
**Symbols:**

```
ffffffff81909810-ffffffff81909ba2: ZSTD_loadDEntropy (STB_GLOBAL)
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
