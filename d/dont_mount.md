# Function: <code>dont_mount</code>

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
In fs/namei.c (ffffffff81218c5f)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
```
```
In fs/fuse/dir.c (ffffffff813141ab)
Location: include/linux/dcache.h:388
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff8124197a)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/fuse/dir.c (ffffffff813487fb)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812549b1)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/fuse/dir.c (ffffffff8135e19e)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff8126045c)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff812dfd19)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81372c9e)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff81282b45)
Location: include/linux/dcache.h:353
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff81304699)
Location: include/linux/dcache.h:353
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8139795e)
Location: include/linux/dcache.h:353
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812ab5d9)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff81332185)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff813c6bb0)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812be1e9)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff81349575)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff813dfd7d)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812daebe)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8137218f)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8140b987)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812ec9ce)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8138a79f)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81425436)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff81326bd7)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff813d5b52)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81474b66)
Location: include/linux/dcache.h:351
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff81332043)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff813e7842)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8148f531)
Location: include/linux/dcache.h:352
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff8133616a)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff813ee212)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81494f51)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff81383ca3)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8143fa22)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff814ec9e1)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff8140449c)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff814bbf8c)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8157b73e)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff8148e91c)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff81553ab7)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81621086)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff814c41ad)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8158b847)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff816594d6)
Location: include/linux/dcache.h:348
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff814f69d5)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff815c457d)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff816931c6)
Location: include/linux/dcache.h:355
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffff800010396060)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffff80001045ad98)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffff800010508b44)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (c057b520)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (c061c968)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:detach_groups
```
```
In fs/fuse/dir.c (c06c4b24)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (c00000000048e60c)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (c0000000005767f4)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (c00000000064e5dc)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffe00026486a)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffe0002eb6a8)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffe000374702)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812e4fae)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff81382d7f)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8141da16)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812d5bee)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8137380f)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff8140e496)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812e2dbe)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8138084f)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81419bb6)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
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
In fs/namei.c (ffffffff812f2cfe)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
```
In fs/configfs/dir.c (ffffffff8139430d)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/fuse/dir.c (ffffffff81430926)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
</details>
</li>
</ul>

## Differences
