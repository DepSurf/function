# Function: <code>HUF_decodeLastSymbolX4</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
U32 HUF_decodeLastSymbolX4(void *op, BIT_DStream_t *DStream, const HUF_DEltX4 *dt, const U32 dtLog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814abc64)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
**Symbols:**

```
ffffffff814ab290-ffffffff814ab2f0: HUF_decodeLastSymbolX4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void *op, BIT_DStream_t *DStream, const HUF_DEltX4 *dt, const U32 dtLog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814e0570)
Location: lib/zstd/huf_decompress.c:603
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
**Symbols:**

```
ffffffff814e0570-ffffffff814e05c9: HUF_decodeLastSymbolX4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void *op, BIT_DStream_t *DStream, const HUF_DEltX4 *dt, const U32 dtLog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814f42c0)
Location: lib/zstd/huf_decompress.c:603
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
**Symbols:**

```
ffffffff814f42c0-ffffffff814f4319: HUF_decodeLastSymbolX4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81521ceb)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81542b7b)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815ce46e)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815ec043)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815cda27)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81638077)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffff80001064fb4c)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c07faed8)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void *op, BIT_DStream_t *DStream, const HUF_DEltX4 *dt, const U32 dtLog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c0000000007fd6d0)
Location: lib/zstd/huf_decompress.c:603
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
**Symbols:**

```
c0000000007fd6d0-c0000000007fd758: HUF_decodeLastSymbolX4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffe00047c13e)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153b15b)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8152b43b)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81536e9b)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81550ccb)
Location: lib/zstd/huf_decompress.c:603
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
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
</ul>
<b>Arch</b>
<ul>
</ul>
