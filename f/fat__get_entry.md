# Function: <code>fat__get_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff812f5eb0)
Location: fs/fat/dir.c:80
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:__fat_readdir
```
**Symbols:**

```
ffffffff812f5eb0-ffffffff812f60e2: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81329500)
Location: fs/fat/dir.c:80
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81329500-ffffffff81329727: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8133f240)
Location: fs/fat/dir.c:80
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff8133f240-ffffffff8133f467: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81353e60)
Location: fs/fat/dir.c:80
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81353e60-ffffffff813540ae: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81378a80)
Location: fs/fat/dir.c:80
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81378a80-ffffffff81378cce: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:81
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813a74f0-ffffffff813a7717: fat__get_entry (STB_LOCAL)
ffffffff813aa8f5-ffffffff813aa914: fat__get_entry.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:81
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813c02e0-ffffffff813c0506: fat__get_entry (STB_LOCAL)
ffffffff813c36d5-ffffffff813c36f4: fat__get_entry.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813eaaf0-ffffffff813ead21: fat__get_entry (STB_LOCAL)
ffffffff813edf35-ffffffff813edf54: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81404b90-ffffffff81404dc1: fat__get_entry (STB_LOCAL)
ffffffff81408055-ffffffff81408074: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81452a00-ffffffff81452c1d: fat__get_entry (STB_LOCAL)
ffffffff81455b15-ffffffff81455b34: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff8146eeb0-ffffffff8146f0cd: fat__get_entry (STB_LOCAL)
ffffffff81bed788-ffffffff81bed7a7: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff814744c0-ffffffff814746da: fat__get_entry (STB_LOCAL)
ffffffff81bdf88b-ffffffff81bdf8aa: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff814cb1e0-ffffffff814cb412: fat__get_entry (STB_LOCAL)
ffffffff81ccf913-ffffffff81ccf96e: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81557290-ffffffff815574f2: fat__get_entry (STB_LOCAL)
ffffffff81e82ae0-ffffffff81e82b3b: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff815f8e60-ffffffff815f90df: fat__get_entry (STB_LOCAL)
ffffffff82071d92-ffffffff82071dce: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81630dc0-ffffffff8163103f: fat__get_entry (STB_LOCAL)
ffffffff820f1a10-ffffffff820f1a4c: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff8166a270-ffffffff8166a4ef: fat__get_entry (STB_LOCAL)
ffffffff821cecf2-ffffffff821ced2e: fat__get_entry.cold (STB_LOCAL)
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
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffff8000104e3890)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffff8000104e3890-ffff8000104e3ab8: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c06a2a34)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
c06a2a34-c06a2d3c: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c000000000620a50)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
c000000000620a50-c000000000620d34: fat__get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffe000356ec4)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffe000356ec4-ffffffe00035707a: fat__get_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813fd170-ffffffff813fd3a1: fat__get_entry (STB_LOCAL)
ffffffff81400635-ffffffff81400654: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813edbf0-ffffffff813ede21: fat__get_entry (STB_LOCAL)
ffffffff813f10b5-ffffffff813f10d4: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff813fa4f0-ffffffff813fa721: fat__get_entry (STB_LOCAL)
ffffffff813fd9b5-ffffffff813fd9d4: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat__get_entry(struct inode *dir, loff_t *pos, struct buffer_head **bh, struct msdos_dir_entry **de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:82
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_get_short_entry
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
```
**Symbols:**

```
ffffffff81410150-ffffffff81410381: fat__get_entry (STB_LOCAL)
ffffffff814135e5-ffffffff81413604: fat__get_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
