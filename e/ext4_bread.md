# Function: <code>ext4_bread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812997a0)
Location: fs/ext4/inode.c:812
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_quota_write
```
**Symbols:**

```
ffffffff812997a0-ffffffff81299848: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6e10)
Location: fs/ext4/inode.c:980
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff812c6e10-ffffffff812c6eba: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc900)
Location: fs/ext4/inode.c:994
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff812dc900-ffffffff812dc9aa: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81301050)
Location: fs/ext4/inode.c:1000
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff81301050-ffffffff813010ee: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325a00)
Location: fs/ext4/inode.c:1010
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff81325a00-ffffffff81325a9e: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353c90)
Location: fs/ext4/inode.c:1011
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff81353c90-ffffffff81353d2e: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136bdd0)
Location: fs/ext4/inode.c:1011
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff8136bdd0-ffffffff8136be6e: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395380)
Location: fs/ext4/inode.c:1019
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff81395380-ffffffff81395421: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813add10)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff813add10-ffffffff813addd2: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9ce0)
Location: fs/ext4/inode.c:877
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff813f9ce0-ffffffff813f9da0: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c330)
Location: fs/ext4/inode.c:893
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff8140c330-ffffffff8140c3a9: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814124b0)
Location: fs/ext4/inode.c:894
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff814124b0-ffffffff81412529: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465290)
Location: fs/ext4/inode.c:895
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff81465290-ffffffff81465301: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e4bf0)
Location: fs/ext4/inode.c:908
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff814e4bf0-ffffffff814e4c69: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157e220)
Location: fs/ext4/inode.c:914
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff8157e220-ffffffff8157e29e: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b5520)
Location: fs/ext4/inode.c:869
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff815b5520-ffffffff815b559e: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ee2d0)
Location: fs/ext4/inode.c:883
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff815ee2d0-ffffffff815ee34e: ext4_bread (STB_GLOBAL)
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
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104825c0)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffff8000104825c0-ffff800010482700: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0643aac)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
c0643aac-c0643bc0: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7080)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
c0000000005a7080-c0000000005a71dc: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030af86)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffe00030af86-ffffffe00030b056: ext4_bread (STB_GLOBAL)
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
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a62f0)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff813a62f0-ffffffff813a63b2: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396d80)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff81396d80-ffffffff81396e42: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3b50)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff813a3b50-ffffffff813a3c12: ext4_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_bread(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8230)
Location: fs/ext4/inode.c:1028
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
```
**Symbols:**

```
ffffffff813b8230-ffffffff813b82e5: ext4_bread (STB_GLOBAL)
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
