# Function: <code>zstd_init_dstream</code>

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
zstd_dstream *zstd_init_dstream(size_t max_window_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff817485a0)
Location: lib/zstd/zstd_decompress_module.c:68
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff817485a0-ffffffff817485d2: zstd_init_dstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
zstd_dstream *zstd_init_dstream(size_t max_window_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff81869d30)
Location: lib/zstd/zstd_decompress_module.c:68
Inline: False
Direct callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff81869d30-ffffffff81869d62: zstd_init_dstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
zstd_dstream *zstd_init_dstream(size_t max_window_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818aa9a0)
Location: lib/zstd/zstd_decompress_module.c:68
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff818aa9a0-ffffffff818aa9d2: zstd_init_dstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
zstd_dstream *zstd_init_dstream(size_t max_window_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_decompress_module.c (ffffffff818fc560)
Location: lib/zstd/zstd_decompress_module.c:68
Inline: False
Direct callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
**Symbols:**

```
ffffffff818fc560-ffffffff818fc592: zstd_init_dstream (STB_GLOBAL)
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
