# Function: <code>ext4_journal_extend</code>

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
In fs/ext4/inode.c (ffffffff8129d96b)
Location: fs/ext4/ext4_jbd2.h:334
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff812beef5)
Location: fs/ext4/ext4_jbd2.h:334
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812c31f2)
Location: fs/ext4/ext4_jbd2.h:334
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812cc10f)
Location: fs/ext4/ext4_jbd2.h:334
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff812d8883)
Location: fs/ext4/ext4_jbd2.h:334
Inline: True
Inline callers:
  - fs/ext4/indirect.c:try_to_extend_transaction
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
In fs/ext4/inode.c (ffffffff812cb642)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff812ee948)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812f2be5)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812fc186)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/indirect.c (ffffffff81308622)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff812e1322)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff81304918)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff81308bb5)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff81312136)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/indirect.c (ffffffff8131e612)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/extents.c (ffffffff812e7386)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff812f786a)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81313bd8)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff8131f4a0)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8133a530)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
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
In fs/ext4/extents.c (ffffffff8130bd86)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff8131beaa)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81338398)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81343b40)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8135e900)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
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
In fs/ext4/extents.c (ffffffff81339491)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff81349d54)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81366933)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813719e1)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8138d248)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
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
In fs/ext4/extents.c (ffffffff813510a1)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff81361f14)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff8137ed88)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81389e7a)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813a5e58)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff81379ca3)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff8138b314)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813a81d7)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b48e7)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813cfeb0)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff813921c3)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff813a3d64)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813c1029)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813cd7e7)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e9580)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/ext4_jbd2.c (ffffffff813dc7cf)
Location: fs/ext4/ext4_jbd2.h:346
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff813ddba0)
Location: fs/ext4/ext4_jbd2.h:346
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/inode.c (ffffffff813f6467)
Location: fs/ext4/ext4_jbd2.h:346
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
In fs/ext4/ext4_jbd2.c (ffffffff813ee21f)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff813ef490)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/inode.c (ffffffff81408dd0)
Location: fs/ext4/ext4_jbd2.h:338
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
In fs/ext4/ext4_jbd2.c (ffffffff813f474f)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff813f595f)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/inode.c (ffffffff81414514)
Location: fs/ext4/ext4_jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/ext4_jbd2.c (ffffffff814468ae)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff814476af)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/inode.c (ffffffff81467894)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/ext4_jbd2.c (ffffffff814c2b02)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff814c35b9)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/inode.c (ffffffff814e7531)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/ext4_jbd2.c (ffffffff8155ae52)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff8155beb9)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/inode.c (ffffffff81580ef1)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/ext4_jbd2.c (ffffffff81592c72)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff81593cc9)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/inode.c (ffffffff815b84a1)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/ext4_jbd2.c (ffffffff815cb992)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
```
```
In fs/ext4/extents.c (ffffffff815cc9b9)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/inode.c (ffffffff815f1241)
Location: fs/ext4/ext4_jbd2.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/extents.c (ffff800010464848)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffff8000104773d0)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffff8000104987cc)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffff8000104a6e24)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffff8000104c24e4)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (c0625504)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (c0638f74)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (c065a114)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0668bd4)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c068643c)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
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
In fs/ext4/extents.c (c000000000586ff8)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/indirect.c (c000000000599600)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (c0000000005c27b4)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0000000005d34e0)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c0000000005f9430)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffe0002f33cc)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffe0003027aa)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffe00031c63a)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffe000326df2)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffe00033d9a8)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff8138a7a3)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff8139c344)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b9609)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c5dc7)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e1b60)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff8137b233)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff8138cdd4)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813aa099)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b6847)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813d25e0)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff81388103)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff81399ba4)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b6e69)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c3257)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813deee0)
Location: fs/ext4/ext4_jbd2.h:335
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
In fs/ext4/extents.c (ffffffff8139be03)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff813adc94)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813cbb79)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813d8402)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813f4300)
Location: fs/ext4/ext4_jbd2.h:335
Inline: True
```
</details>
</li>
</ul>

## Differences
