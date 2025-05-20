# Function: <code>zstd_get_frame_header</code>

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
size_t zstd_get_frame_header(zstd_frame_header *header, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81748640)
Location: lib/zstd/zstd_decompress_module.c:97
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81748640-ffffffff8174865a: zstd_get_frame_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t zstd_get_frame_header(zstd_frame_header *header, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869e10)
Location: lib/zstd/zstd_decompress_module.c:97
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81869e10-ffffffff81869e2a: zstd_get_frame_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zstd_get_frame_header(zstd_frame_header *header, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aaa80)
Location: lib/zstd/zstd_decompress_module.c:97
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818aaa80-ffffffff818aaa9a: zstd_get_frame_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zstd_get_frame_header(zstd_frame_header *header, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc640)
Location: lib/zstd/zstd_decompress_module.c:97
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818fc640-ffffffff818fc65a: zstd_get_frame_header (STB_GLOBAL)
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
