# Function: <code>HUF_decompress4X2_usingDTable_internal_bmi2</code>

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
size_t HUF_decompress4X2_usingDTable_internal_bmi2(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174b980)
Location: lib/zstd/decompress/huf_decompress.c:919
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
```
**Symbols:**

```
ffffffff8174b980-ffffffff8174d1d4: HUF_decompress4X2_usingDTable_internal_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_decompress4X2_usingDTable_internal_bmi2(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8186e130)
Location: lib/zstd/decompress/huf_decompress.c:1363
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
```
**Symbols:**

```
ffffffff8186e130-ffffffff818704b2: HUF_decompress4X2_usingDTable_internal_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_decompress4X2_usingDTable_internal_bmi2(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818aee10)
Location: lib/zstd/decompress/huf_decompress.c:1363
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
```
**Symbols:**

```
ffffffff818aee10-ffffffff818b1195: HUF_decompress4X2_usingDTable_internal_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_decompress4X2_usingDTable_internal_bmi2(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff819009d0)
Location: lib/zstd/decompress/huf_decompress.c:1363
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
```
**Symbols:**

```
ffffffff819009d0-ffffffff81902d55: HUF_decompress4X2_usingDTable_internal_bmi2 (STB_LOCAL)
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
