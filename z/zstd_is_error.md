# Function: <code>zstd_is_error</code>

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
unsigned int zstd_is_error(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff817484b0)
Location: lib/zstd/zstd_decompress_module.c:21
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/policy_unpack.c:compress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff817484b0-ffffffff817484c6: zstd_is_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int zstd_is_error(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869bd0)
Location: lib/zstd/zstd_decompress_module.c:21
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff81869bd0-ffffffff81869be6: zstd_is_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int zstd_is_error(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aa840)
Location: lib/zstd/zstd_decompress_module.c:21
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff818aa840-ffffffff818aa856: zstd_is_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int zstd_is_error(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc400)
Location: lib/zstd/zstd_decompress_module.c:21
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - lib/decompress_unzstd.c:handle_zstd_error
```
**Symbols:**

```
ffffffff818fc400-ffffffff818fc416: zstd_is_error (STB_GLOBAL)
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
