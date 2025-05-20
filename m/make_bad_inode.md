# Function: <code>make_bad_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81229a30)
Location: fs/bad_inode.c:170
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/super.c:ext4_load_journal
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81229a30-ffffffff81229a9c: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81252180)
Location: fs/bad_inode.c:170
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81252180-ffffffff812521ec: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812653d0)
Location: fs/bad_inode.c:197
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812653d0-ffffffff81265440: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81272be0)
Location: fs/bad_inode.c:197
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81272be0-ffffffff81272c54: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81295510)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81295510-ffffffff81295584: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812bb720)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812bb720-ffffffff812bb790: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812d0910)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812d0910-ffffffff812d0980: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed9b0)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812ed9b0-ffffffff812eda20: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff470)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812ff470-ffffffff812ff4e0: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813384f0)
Location: fs/bad_inode.c:199
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff813384f0-ffffffff81338563: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81343e80)
Location: fs/bad_inode.c:199
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
```
**Symbols:**

```
ffffffff81343e80-ffffffff81343ef3: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8134a230)
Location: fs/bad_inode.c:207
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8134a230-ffffffff8134a2a3: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81397f90)
Location: fs/bad_inode.c:207
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81397f90-ffffffff81398003: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8141a530)
Location: fs/bad_inode.c:207
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8141a530-ffffffff8141a5ad: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814a63a0)
Location: fs/bad_inode.c:207
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff814a63a0-ffffffff814a641d: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814db360)
Location: fs/bad_inode.c:207
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff814db360-ffffffff814db3dd: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8150dac5)
Location: fs/bad_inode.c:206
Inline: True
Inline callers:
  - fs/bad_inode.c:iget_failed
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_statx
```
**Symbols:**

```
ffffffff8150d950-ffffffff8150d9b2: make_bad_inode (STB_GLOBAL)
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
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffff8000103b08e8)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffff8000103b08e8-ffff8000103b0964: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c05901d0)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
c05901d0-c0590294: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac280)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
c0000000004ac280-c0000000004ac324: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffe000274c42)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffe000274c42-ffffffe000274cb4: make_bad_inode (STB_GLOBAL)
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
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f7a50)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812f7a50-ffffffff812f7ac0: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e8670)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812e8670-ffffffff812e86e0: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f5860)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812f5860-ffffffff812f58d0: make_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void make_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813069f0)
Location: fs/bad_inode.c:198
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff813069f0-ffffffff81306a60: make_bad_inode (STB_GLOBAL)
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
