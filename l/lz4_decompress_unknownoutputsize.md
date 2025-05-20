# Function: <code>lz4_decompress_unknownoutputsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lz4_decompress_unknownoutputsize(const unsigned char *src, size_t src_len, unsigned char *dest, size_t *dest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8140e930)
Location: lib/lz4/lz4_decompress.c:322
Inline: False
Direct callers:
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8140e930-ffffffff8140ebe3: lz4_decompress_unknownoutputsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lz4_decompress_unknownoutputsize(const unsigned char *src, size_t src_len, unsigned char *dest, size_t *dest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81456650)
Location: lib/lz4/lz4_decompress.c:322
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81456650-ffffffff81456902: lz4_decompress_unknownoutputsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lz4_decompress_unknownoutputsize(const unsigned char *src, size_t src_len, unsigned char *dest, size_t *dest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81475010)
Location: lib/lz4/lz4_decompress.c:322
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81475010-ffffffff814752c2: lz4_decompress_unknownoutputsize (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
