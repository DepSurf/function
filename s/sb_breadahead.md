# Function: <code>sb_breadahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81296667)
Location: include/linux/buffer_head.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/fat/dir.c (ffffffff812f5fb4)
Location: include/linux/buffer_head.h:307
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff812fa63b)
Location: include/linux/buffer_head.h:307
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c3c59)
Location: include/linux/buffer_head.h:311
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/fat/dir.c (ffffffff81329602)
Location: include/linux/buffer_head.h:311
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8132e25f)
Location: include/linux/buffer_head.h:311
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9309)
Location: include/linux/buffer_head.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/fat/dir.c (ffffffff8133f342)
Location: include/linux/buffer_head.h:314
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81343f9f)
Location: include/linux/buffer_head.h:314
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ff9bc)
Location: include/linux/buffer_head.h:315
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff81336b5a)
Location: include/linux/buffer_head.h:315
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff81353ff6)
Location: include/linux/buffer_head.h:315
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81358a50)
Location: include/linux/buffer_head.h:315
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132416f)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff8135b108)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff81378c16)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8137d75a)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81350b32)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff8138996d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813a7616)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813ac18d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81369fc2)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813a24f5)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813c0405)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813c3f8e)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393407)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813cce2a)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813eac1d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813ee73e)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813abdb5)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813e62f7)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff81404cbd)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8140877e)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81452b0d)
Location: include/linux/buffer_head.h:311
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814563cf)
Location: include/linux/buffer_head.h:311
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8146efbd)
Location: include/linux/buffer_head.h:311
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8147278f)
Location: include/linux/buffer_head.h:311
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff814745ca)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814781a8)
Location: include/linux/buffer_head.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff814cb2f6)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814cf578)
Location: include/linux/buffer_head.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff815573d2)
Location: include/linux/buffer_head.h:335
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8155c113)
Location: include/linux/buffer_head.h:335
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff815f8f9d)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff815fe023)
Location: include/linux/buffer_head.h:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81630efd)
Location: include/linux/buffer_head.h:361
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81635ff3)
Location: include/linux/buffer_head.h:361
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8166a3ad)
Location: include/linux/buffer_head.h:331
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8166f4e3)
Location: include/linux/buffer_head.h:331
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104805e8)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffff8000104bf5c0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffff8000104e39a0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffff8000104e8c70)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0641aa8)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (c0683204)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (c06a2bd4)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c06a6980)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_reada
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a4d10)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (c0000000005f5c90)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (c000000000620bc0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c000000000626930)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe0003092e6)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffe00033a89c)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffe000356f90)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffe00035a128)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4395)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813de8d7)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813fd29d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81400d5e)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394e25)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813cf357)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813edd1d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813f17de)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1bf5)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813dbc94)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff813fa61d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813fe0de)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b684f)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813f1047)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/dir.c (ffffffff8141027d)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81413e3e)
Location: include/linux/buffer_head.h:317
Inline: True
```
</details>
</li>
</ul>

## Differences
