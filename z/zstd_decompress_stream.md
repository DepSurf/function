# Function: <code>zstd_decompress_stream</code>

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
size_t zstd_decompress_stream(zstd_dstream *dstream, zstd_out_buffer *output, zstd_in_buffer *input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81748600)
Location: lib/zstd/zstd_decompress_module.c:84
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff81748600-ffffffff8174861a: zstd_decompress_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t zstd_decompress_stream(zstd_dstream *dstream, zstd_out_buffer *output, zstd_in_buffer *input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869db0)
Location: lib/zstd/zstd_decompress_module.c:84
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff81869db0-ffffffff81869dca: zstd_decompress_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zstd_decompress_stream(zstd_dstream *dstream, zstd_out_buffer *output, zstd_in_buffer *input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aaa20)
Location: lib/zstd/zstd_decompress_module.c:84
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff818aaa20-ffffffff818aaa3a: zstd_decompress_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zstd_decompress_stream(zstd_dstream *dstream, zstd_out_buffer *output, zstd_in_buffer *input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc5e0)
Location: lib/zstd/zstd_decompress_module.c:84
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff818fc5e0-ffffffff818fc5fa: zstd_decompress_stream (STB_GLOBAL)
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
