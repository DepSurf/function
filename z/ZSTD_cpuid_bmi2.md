# Function: <code>ZSTD_cpuid_bmi2</code>

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
In lib/zstd/compress/zstd_compress.c (ffffffff81715209)
Location: lib/zstd/common/cpu.h:166
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff817536e2)
Location: lib/zstd/common/cpu.h:166
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
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
In lib/zstd/compress/zstd_compress.c (ffffffff81809009)
Location: lib/zstd/common/cpu.h:166
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCCtx
```
```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/common/cpu.h:166
Inline: True
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
In lib/zstd/compress/zstd_compress.c (ffffffff818499f9)
Location: lib/zstd/common/cpu.h:166
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCCtx
```
```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/common/cpu.h:166
Inline: True
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
In lib/zstd/compress/zstd_compress.c (ffffffff8189b5b9)
Location: lib/zstd/common/cpu.h:166
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCCtx
```
```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/common/cpu.h:166
Inline: True
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
