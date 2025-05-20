# Function: <code>ZSTD_createCStream_advanced</code>

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
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbf70)
Location: lib/zstd/compress.c:2982
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815cbf70-ffffffff815cc08d: ZSTD_createCStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e9ab0)
Location: lib/zstd/compress.c:2982
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815e9ab0-ffffffff815e9bd2: ZSTD_createCStream_advanced (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bb95)
Location: lib/zstd/compress/zstd_compress.c:3932
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
```
**Symbols:**

```
ffffffff8171bbe0-ffffffff8171bbfd: ZSTD_createCStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818112d5)
Location: lib/zstd/compress/zstd_compress.c:5048
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
```
**Symbols:**

```
ffffffff81811340-ffffffff8181135d: ZSTD_createCStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81851db5)
Location: lib/zstd/compress/zstd_compress.c:5048
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
```
**Symbols:**

```
ffffffff81851e20-ffffffff81851e3d: ZSTD_createCStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CStream *ZSTD_createCStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3975)
Location: lib/zstd/compress/zstd_compress.c:5048
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
```
**Symbols:**

```
ffffffff818a39e0-ffffffff818a39fd: ZSTD_createCStream_advanced (STB_GLOBAL)
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
