# Function: <code>ZSTD_resetCStream_internal</code>

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
size_t ZSTD_resetCStream_internal(ZSTD_CStream *zcs, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b7eea)
Location: lib/zstd/compress.c:3026
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815b8130-ffffffff815b8365: ZSTD_resetCStream_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_resetCStream_internal(ZSTD_CStream *zcs, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d53cf)
Location: lib/zstd/compress.c:3026
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815d5610-ffffffff815d584a: ZSTD_resetCStream_internal (STB_LOCAL)
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
