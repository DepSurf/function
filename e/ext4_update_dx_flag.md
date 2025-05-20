# Function: <code>ext4_update_dx_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a19f0)
Location: fs/ext4/ext4.h:2363
Inline: True
Inline callers:
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/inline.c (ffffffff812e03f8)
Location: fs/ext4/ext4.h:2363
Inline: True
```
**Symbols:**

```
ffffffff812a19f0-ffffffff812a19fb: ext4_update_dx_flag.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d6bb2)
Location: fs/ext4/ext4.h:2391
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/inline.c (ffffffff813100bf)
Location: fs/ext4/ext4.h:2391
Inline: True
```
**Symbols:**

```
ffffffff812d0920-ffffffff812d092e: ext4_update_dx_flag.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812ec86c)
Location: fs/ext4/ext4.h:2371
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/inline.c (ffffffff81325c9e)
Location: fs/ext4/ext4.h:2371
Inline: True
```
**Symbols:**

```
ffffffff812e66c0-ffffffff812e66ce: ext4_update_dx_flag.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9ce1)
Location: fs/ext4/ext4.h:2384
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8131c4c3)
Location: fs/ext4/ext4.h:2384
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81316360-ffffffff8131636e: ext4_update_dx_flag.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131e311)
Location: fs/ext4/ext4.h:2344
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81340ab2)
Location: fs/ext4/ext4.h:2344
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8133abd0-ffffffff8133abde: ext4_update_dx_flag.part.21 (STB_LOCAL)
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
In fs/ext4/inline.c (ffffffff8134c520)
Location: fs/ext4/ext4.h:2345
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8136eaad)
Location: fs/ext4/ext4.h:2345
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff81364660)
Location: fs/ext4/ext4.h:2358
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81386f3d)
Location: fs/ext4/ext4.h:2358
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8138cf52)
Location: fs/ext4/ext4.h:2439
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813b0ecd)
Location: fs/ext4/ext4.h:2439
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff813a59a2)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813c9ef6)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff813f18f2)
Location: fs/ext4/ext4.h:2595
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff8141585e)
Location: fs/ext4/ext4.h:2595
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff81404412)
Location: fs/ext4/ext4.h:2727
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff81428f0d)
Location: fs/ext4/ext4.h:2727
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8140a9f5)
Location: fs/ext4/ext4.h:2780
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff8142fa16)
Location: fs/ext4/ext4.h:2780
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8145d64f)
Location: fs/ext4/ext4.h:2850
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff81484066)
Location: fs/ext4/ext4.h:2850
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff814db89a)
Location: fs/ext4/ext4.h:2807
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff8150720b)
Location: fs/ext4/ext4.h:2807
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ext4_update_dx_flag(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8157428b)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff815a1cce)
Location: fs/ext4/ext4.h:2817
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8159ad50-ffffffff8159ad8e: ext4_update_dx_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ext4_update_dx_flag(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ac0db)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff815d8653)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff815d15d0-ffffffff815d160e: ext4_update_dx_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ext4_update_dx_flag(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e4e70)
Location: fs/ext4/ext4.h:2826
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (ffffffff81610c8f)
Location: fs/ext4/ext4.h:2826
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81609d70-ffffffff81609dae: ext4_update_dx_flag (STB_LOCAL)
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
In fs/ext4/inline.c (ffff800010479184)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffff8000104a1a84)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (c063aeac)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/namei.c (c0663c40)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (c00000000059bd6c)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (c0000000005ce5d4)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffe0003044c0)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffe0003239d0)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8139df82)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813c24d6)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8138ea12)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813b2f66)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8139b7e2)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813bf986)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff813afca2)
Location: fs/ext4/ext4.h:2497
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813d4a66)
Location: fs/ext4/ext4.h:2497
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:add_dirent_to_buf
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
