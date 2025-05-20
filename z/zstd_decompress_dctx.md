# Function: <code>zstd_decompress_dctx</code>

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
size_t zstd_decompress_dctx(zstd_dctx *dctx, void *dst, size_t dst_capacity, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81748560)
Location: lib/zstd/zstd_decompress_module.c:55
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81748560-ffffffff8174857f: zstd_decompress_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t zstd_decompress_dctx(zstd_dctx *dctx, void *dst, size_t dst_capacity, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869cd0)
Location: lib/zstd/zstd_decompress_module.c:55
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81869cd0-ffffffff81869cef: zstd_decompress_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zstd_decompress_dctx(zstd_dctx *dctx, void *dst, size_t dst_capacity, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aa940)
Location: lib/zstd/zstd_decompress_module.c:55
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818aa940-ffffffff818aa95f: zstd_decompress_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zstd_decompress_dctx(zstd_dctx *dctx, void *dst, size_t dst_capacity, const void *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc500)
Location: lib/zstd/zstd_decompress_module.c:55
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818fc500-ffffffff818fc51f: zstd_decompress_dctx (STB_GLOBAL)
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
