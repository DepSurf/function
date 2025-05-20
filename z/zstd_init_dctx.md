# Function: <code>zstd_init_dctx</code>

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
zstd_dctx *zstd_init_dctx(void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81748530)
Location: lib/zstd/zstd_decompress_module.c:47
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81748530-ffffffff81748558: zstd_init_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
zstd_dctx *zstd_init_dctx(void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869c90)
Location: lib/zstd/zstd_decompress_module.c:47
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff81869c90-ffffffff81869cb8: zstd_init_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
zstd_dctx *zstd_init_dctx(void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aa900)
Location: lib/zstd/zstd_decompress_module.c:47
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818aa900-ffffffff818aa928: zstd_init_dctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
zstd_dctx *zstd_init_dctx(void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc4c0)
Location: lib/zstd/zstd_decompress_module.c:47
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
```
**Symbols:**

```
ffffffff818fc4c0-ffffffff818fc4e8: zstd_init_dctx (STB_GLOBAL)
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
