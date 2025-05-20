# Function: <code>FSE_flushCState</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac116)
Location: lib/zstd/fse.h:462
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress.c (ffffffff815c995d)
Location: lib/zstd/fse.h:462
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7c06)
Location: lib/zstd/fse.h:462
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress.c (ffffffff815e7520)
Location: lib/zstd/fse.h:462
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170e0c7)
Location: lib/zstd/common/fse.h:545
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8171d596)
Location: lib/zstd/common/fse.h:545
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff817fd037)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81812eb1)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff8183d900)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8185386a)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff8188f4c0)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff818a542a)
Location: lib/zstd/common/fse.h:546
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
