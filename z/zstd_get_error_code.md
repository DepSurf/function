# Function: <code>zstd_get_error_code</code>

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
zstd_error_code zstd_get_error_code(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff817484d0)
Location: lib/zstd/zstd_decompress_module.c:27
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - lib/decompress_unzstd.c:handle_zstd_error
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff817484d0-ffffffff817484e6: zstd_get_error_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
zstd_error_code zstd_get_error_code(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869c00)
Location: lib/zstd/zstd_decompress_module.c:27
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff81869c00-ffffffff81869c16: zstd_get_error_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
zstd_error_code zstd_get_error_code(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aa870)
Location: lib/zstd/zstd_decompress_module.c:27
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff818aa870-ffffffff818aa886: zstd_get_error_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
zstd_error_code zstd_get_error_code(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc430)
Location: lib/zstd/zstd_decompress_module.c:27
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff818fc430-ffffffff818fc446: zstd_get_error_code (STB_GLOBAL)
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
