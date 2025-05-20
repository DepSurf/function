# Function: <code>ZSTD_window_correctOverflow</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171319c)
Location: lib/zstd/compress/zstd_compress_internal.h:826
Inline: True
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff81743d21)
Location: lib/zstd/compress/zstd_compress_internal.h:826
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180676c)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185d648)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184713c)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189e1f8)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81898cfc)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff818efdb8)
Location: lib/zstd/compress/zstd_compress_internal.h:1014
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences
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
