# Function: <code>ZSTD_initCStream_usingCDict</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
ZSTD_CStream *ZSTD_initCStream_usingCDict(const ZSTD_CDict *cdict, long long unsigned int pledgedSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc2e0)
Location: lib/zstd/compress.c:3105
Inline: False
```
**Symbols:**

```
ffffffff815cc2e0-ffffffff815cc550: ZSTD_initCStream_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ZSTD_CStream *ZSTD_initCStream_usingCDict(const ZSTD_CDict *cdict, long long unsigned int pledgedSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e9e30)
Location: lib/zstd/compress.c:3105
Inline: False
```
**Symbols:**

```
ffffffff815e9e30-ffffffff815ea0a5: ZSTD_initCStream_usingCDict (STB_GLOBAL)
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
size_t ZSTD_initCStream_usingCDict(ZSTD_CStream *zcs, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bd70)
Location: lib/zstd/compress/zstd_compress.c:4016
Inline: False
```
**Symbols:**

```
ffffffff8171bd70-ffffffff8171bdb2: ZSTD_initCStream_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_initCStream_usingCDict(ZSTD_CStream *zcs, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811540)
Location: lib/zstd/compress/zstd_compress.c:5132
Inline: False
```
**Symbols:**

```
ffffffff81811540-ffffffff81811582: ZSTD_initCStream_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_initCStream_usingCDict(ZSTD_CStream *zcs, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852020)
Location: lib/zstd/compress/zstd_compress.c:5132
Inline: False
```
**Symbols:**

```
ffffffff81852020-ffffffff81852062: ZSTD_initCStream_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_initCStream_usingCDict(ZSTD_CStream *zcs, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3be0)
Location: lib/zstd/compress/zstd_compress.c:5132
Inline: False
```
**Symbols:**

```
ffffffff818a3be0-ffffffff818a3c22: ZSTD_initCStream_usingCDict (STB_GLOBAL)
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
