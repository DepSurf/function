# Function: <code>__d_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223530)
Location: fs/dcache.c:468
Inline: False
Direct callers:
  - fs/namei.c:dentry_unhash
  - fs/dcache.c:d_drop
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81223530-ffffffff812235bc: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124bc20)
Location: fs/dcache.c:439
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
```
**Symbols:**

```
ffffffff8124bc20-ffffffff8124bc9f: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ec00)
Location: fs/dcache.c:439
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
```
**Symbols:**

```
ffffffff8125ec00-ffffffff8125ec7f: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c5d0)
Location: fs/dcache.c:473
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff8126c5d0-ffffffff8126c64f: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128f5e5)
Location: fs/dcache.c:497
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff8128e950-ffffffff8128e96d: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812b4e52)
Location: fs/dcache.c:481
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812b48c0-ffffffff812b48e1: __d_drop.part.31 (STB_LOCAL)
ffffffff812b48f0-ffffffff812b4908: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812ca0b2)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812c9b40-ffffffff812c9b61: __d_drop.part.30 (STB_LOCAL)
ffffffff812c9b70-ffffffff812c9b88: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812e70ba)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812e6550-ffffffff812e6571: __d_drop.part.0 (STB_LOCAL)
ffffffff812e6580-ffffffff812e6598: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812f8c2a)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812f80b0-ffffffff812f80d1: __d_drop.part.0 (STB_LOCAL)
ffffffff812f80e0-ffffffff812f80f8: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333b37)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81330e30-ffffffff81330e5c: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f4b7)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff8133c7c0-ffffffff8133c7ec: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345937)
Location: fs/dcache.c:479
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81342c40-ffffffff81342c6c: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81393547)
Location: fs/dcache.c:479
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81390680-ffffffff813906ac: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414c86)
Location: fs/dcache.c:504
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81413040-ffffffff81413078: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a01a6)
Location: fs/dcache.c:504
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff8149e2d0-ffffffff8149e308: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d54c6)
Location: fs/dcache.c:504
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff814d35f0-ffffffff814d3628: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815078e6)
Location: fs/dcache.c:505
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81505d70-ffffffff81505da8: __d_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffff8000103a6dd0)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffff8000103a55e8-ffff8000103a5628: __d_drop.part.0 (STB_LOCAL)
ffff8000103a5628-ffff8000103a565c: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (c0588c40)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
c0588b58-c0588b90: __d_drop.part.0 (STB_LOCAL)
c0588b90-c0588bb8: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (c0000000004a0c30)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
c0000000004a0aa0-c0000000004a0af4: __d_drop.part.0 (STB_LOCAL)
c0000000004a0b00-c0000000004a0b20: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffe00026d642)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffe00026c370-ffffffe00026c3a8: __d_drop.part.0 (STB_LOCAL)
ffffffe00026c3a8-ffffffe00026c3d6: __d_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812f120a)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812f0690-ffffffff812f06b1: __d_drop.part.0 (STB_LOCAL)
ffffffff812f06c0-ffffffff812f06d8: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812e1e3a)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812e12c0-ffffffff812e12e1: __d_drop.part.0 (STB_LOCAL)
ffffffff812e12f0-ffffffff812e1308: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812ef01a)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff812ee4a0-ffffffff812ee4c1: __d_drop.part.0 (STB_LOCAL)
ffffffff812ee4d0-ffffffff812ee4e8: __d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff8130039a)
Location: fs/dcache.c:494
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/configfs/inode.c:configfs_drop_dentry
```
**Symbols:**

```
ffffffff81300230-ffffffff81300251: __d_drop.part.0 (STB_LOCAL)
ffffffff81300260-ffffffff81300278: __d_drop (STB_GLOBAL)
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
