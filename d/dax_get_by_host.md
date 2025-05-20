# Function: <code>dax_get_by_host</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cdd0)
Location: drivers/dax/super.c:482
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/inode.c:ext4_iomap_begin
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8163cdd0-ffffffff8163ce8d: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5aa0)
Location: drivers/dax/super.c:511
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff816a5aa0-ffffffff816a5b5d: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1ec0)
Location: drivers/dax/super.c:537
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff816e1ec0-ffffffff816e1f85: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817052e0)
Location: drivers/dax/super.c:536
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff817052e0-ffffffff817053a5: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f170)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8173f170-ffffffff8173f249: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763350)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81763350-ffffffff81763429: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818231f0)
Location: drivers/dax/super.c:623
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff818231f0-ffffffff818232c9: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831f30)
Location: drivers/dax/super.c:631
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81831f30-ffffffff81832009: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81815660)
Location: drivers/dax/super.c:631
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81815660-ffffffff81815739: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189fe00)
Location: drivers/dax/super.c:70
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff8189fe00-ffffffff8189fedc: dax_get_by_host (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963030)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffff800010963030-ffff800010963170: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a35c)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c0a3a35c-c0a3a47c: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a194c0)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c000000000a194c0-c000000000a197f8: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d071c)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffe0005d071c-ffffffe0005d0832: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717a40)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81717a40-ffffffff81717b19: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816eff70)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff816eff70-ffffffff816f0049: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756810)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81756810-ffffffff817568e9: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dax_device *dax_get_by_host(const char *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771c70)
Location: drivers/dax/super.c:595
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:dax_visible
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81771c70-ffffffff81771d47: dax_get_by_host (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
