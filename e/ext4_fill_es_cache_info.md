# Function: <code>ext4_fill_es_cache_info</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813916d0)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffff813916d0-ffffffff81391804: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd1b0)
Location: fs/ext4/extents.c:2139
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff813dd1b0-ffffffff813dd2e4: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813eeaa0)
Location: fs/ext4/extents.c:2138
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff813eeaa0-ffffffff813eebd4: ext4_fill_es_cache_info (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff813fd3ce)
Location: fs/ext4/extents.c:2141
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2179
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff81447300-ffffffff81447435: ext4_fill_es_cache_info (STB_LOCAL)
ffffffff81cc8ef4-ffffffff81cc8f66: ext4_fill_es_cache_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2178
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff814c3970-ffffffff814c3af9: ext4_fill_es_cache_info (STB_LOCAL)
ffffffff81e7bc50-ffffffff81e7bcc2: ext4_fill_es_cache_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2185
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff8155bcb0-ffffffff8155be39: ext4_fill_es_cache_info (STB_LOCAL)
ffffffff8206c2d5-ffffffff8206c347: ext4_fill_es_cache_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2185
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff81593ad0-ffffffff81593c49: ext4_fill_es_cache_info (STB_LOCAL)
ffffffff820ec167-ffffffff820ec1c0: ext4_fill_es_cache_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2185
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
**Symbols:**

```
ffffffff815cc7c0-ffffffff815cc939: ext4_fill_es_cache_info (STB_LOCAL)
ffffffff821c939f-ffffffff821c93f8: ext4_fill_es_cache_info.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104642b0)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffff8000104642b0-ffff8000104643e0: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0625288)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
c0625288-c0625430: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582490)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
c000000000582490-c000000000582658: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f31b2)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffe0002f31b2-ffffffe0002f32b2: ext4_fill_es_cache_info (STB_LOCAL)
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
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389cb0)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffff81389cb0-ffffffff81389de4: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a740)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffff8137a740-ffffffff8137a874: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387610)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffff81387610-ffffffff81387744: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b2f0)
Location: fs/ext4/extents.c:2318
Inline: False
```
**Symbols:**

```
ffffffff8139b2f0-ffffffff8139b424: ext4_fill_es_cache_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
