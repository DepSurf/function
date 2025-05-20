# Function: <code>iomap_swapfile_activate</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130fb50)
Location: fs/iomap.c:1378
Inline: False
```
**Symbols:**

```
ffffffff8130fb50-ffffffff8130fc84: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326ae0)
Location: fs/iomap.c:2093
Inline: False
```
**Symbols:**

```
ffffffff81326ae0-ffffffff81326c11: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff8134e5f0)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff8134e5f0-ffffffff8134e716: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff813668e0)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff813668e0-ffffffff81366a06: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff813ae440)
Location: fs/iomap/swapfile.c:135
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff813ae440-ffffffff813ae566: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:135
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81bebb7e-ffffffff81bebb94: iomap_swapfile_activate.cold (STB_LOCAL)
ffffffff813bfab0-ffffffff813bfbe0: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:140
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81bddc0b-ffffffff81bddc21: iomap_swapfile_activate.cold (STB_LOCAL)
ffffffff813c6900-ffffffff813c6a34: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:142
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81cc7bee-ffffffff81cc7c04: iomap_swapfile_activate.cold (STB_LOCAL)
ffffffff81416db0-ffffffff81416f05: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:142
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81e7a7ee-ffffffff81e7a804: iomap_swapfile_activate.cold (STB_LOCAL)
ffffffff8148e3e0-ffffffff8148e544: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81521c80)
Location: fs/iomap/swapfile.c:142
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81521c80-ffffffff81521df2: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81559cc0)
Location: fs/iomap/swapfile.c:142
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81559cc0-ffffffff81559e32: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81590480)
Location: fs/iomap/swapfile.c:142
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_swap_activate
```
**Symbols:**

```
ffffffff81590480-ffffffff815905f2: iomap_swapfile_activate (STB_GLOBAL)
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
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffff80001042e108)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffff80001042e108-ffff80001042e254: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (c05f72c4)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
c05f72c4-c05f74b4: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (c00000000053f4e0)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
c00000000053f4e0-c00000000053f684: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffe0002caa22)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffe0002caa22-ffffffe0002cab2c: iomap_swapfile_activate (STB_GLOBAL)
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
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff8135eec0)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff8135eec0-ffffffff8135efe6: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff8134fb60)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff8134fb60-ffffffff8134fc86: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff8135c990)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff8135c990-ffffffff8135cab6: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *pagespan, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81370100)
Location: fs/iomap/swapfile.c:134
Inline: False
```
**Symbols:**

```
ffffffff81370100-ffffffff81370226: iomap_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
