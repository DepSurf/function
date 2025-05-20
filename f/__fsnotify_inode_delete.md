# Function: <code>__fsnotify_inode_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8124f270)
Location: fs/notify/fsnotify.c:33
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
  - fs/inode.c:__destroy_inode
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
```
**Symbols:**

```
ffffffff8124f270-ffffffff8124f28e: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812779d0)
Location: fs/notify/fsnotify.c:33
Inline: False
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
```
**Symbols:**

```
ffffffff812779d0-ffffffff812779ee: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8128b6b0)
Location: fs/notify/fsnotify.c:33
Inline: False
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
```
**Symbols:**

```
ffffffff8128b6b0-ffffffff8128b6ce: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81298c78)
Location: fs/notify/fsnotify.c:33
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812984b0-ffffffff812984c7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812bc008)
Location: fs/notify/fsnotify.c:33
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812bb7b0-ffffffff812bb7c7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e4c2a)
Location: fs/notify/fsnotify.c:33
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812e4350-ffffffff812e4367: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812f96b5)
Location: fs/notify/fsnotify.c:33
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812f8fd0-ffffffff812f8fe7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81319d15)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81319610-ffffffff81319627: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8132cb45)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8132c440-ffffffff8132c457: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81366695)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813661a0-ffffffff813661b7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8137380d)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813730b0-ffffffff813730c7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8137a16d)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81379a30-ffffffff81379a47: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c6e2b)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813c6590-ffffffff813c65a7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144e162)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8144d540-ffffffff8144d55d: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dc852)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff814dbb30-ffffffff814dbb4d: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff815130a2)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81512320-ffffffff8151233d: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81547552)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff815467d0-ffffffff815467ed: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffff8000103e855c)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffff8000103e7d18-ffff8000103e7d44: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c05bfefc)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c05bf77c-c05bf79c: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c0000000004eefc0)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c0000000004ee500-c0000000004ee538: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffe00029d224)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffe00029cb20-ffffffe00029cb4c: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81325125)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81324a20-ffffffff81324a37: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81315cc5)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813155c0-ffffffff813155d7: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81322bf5)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813224f0-ffffffff81322507: __fsnotify_inode_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_inode_delete(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81334941)
Location: fs/notify/fsnotify.c:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
Direct callers:
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81334240-ffffffff81334257: __fsnotify_inode_delete (STB_GLOBAL)
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
