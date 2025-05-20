# Function: <code>mdname</code>

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
In drivers/md/md.c (ffffffff8168d970)
Location: drivers/md/md.h:561
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/bitmap.c (ffffffff8169d47d)
Location: drivers/md/md.h:561
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
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
In drivers/md/md.c (ffffffff816f5139)
Location: drivers/md/md.h:538
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/bitmap.c (ffffffff8170065b)
Location: drivers/md/md.h:538
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
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
In drivers/md/md.c (ffffffff817267c9)
Location: drivers/md/md.h:564
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/bitmap.c (ffffffff81732653)
Location: drivers/md/md.h:564
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
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
In drivers/md/md.c (ffffffff8173eb92)
Location: drivers/md/md.h:577
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/bitmap.c (ffffffff8174b3a3)
Location: drivers/md/md.h:577
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_wait_behind_writes
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
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
In drivers/md/md.c (ffffffff817b0802)
Location: drivers/md/md.h:583
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff817bd705)
Location: drivers/md/md.h:583
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_print_sb
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
In drivers/md/md.c (ffffffff817fffb9)
Location: drivers/md/md.h:600
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8180560d)
Location: drivers/md/md.h:600
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_print_sb
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
In drivers/md/md.c (ffffffff81829cf7)
Location: drivers/md/md.h:602
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8183180d)
Location: drivers/md/md.h:602
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff8186c1f0)
Location: drivers/md/md.h:611
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff81874234)
Location: drivers/md/md.h:611
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff8189dfd8)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff818a6044)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff8196e30c)
Location: drivers/md/md.h:627
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff81975e3c)
Location: drivers/md/md.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff819753e0)
Location: drivers/md/md.h:630
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8197ae2c)
Location: drivers/md/md.h:630
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff8195941f)
Location: drivers/md/md.h:629
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8195f05c)
Location: drivers/md/md.h:629
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff819febbf)
Location: drivers/md/md.h:630
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff81a04999)
Location: drivers/md/md.h:630
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81b661bd)
Location: drivers/md/md.h:638
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff81ef58ec)
Location: drivers/md/md.h:638
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81d013b1)
Location: drivers/md/md.h:655
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_check_no_bitmap
```
```
In drivers/md/md-bitmap.c (ffffffff81d05b2c)
Location: drivers/md/md.h:655
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81d6a70e)
Location: drivers/md/md.h:677
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_check_no_bitmap
```
```
In drivers/md/md-bitmap.c (ffffffff81d6fb89)
Location: drivers/md/md.h:677
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81e21282)
Location: drivers/md/md.h:658
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:md_check_no_bitmap
```
```
In drivers/md/md-bitmap.c (ffffffff81e25b8d)
Location: drivers/md/md.h:658
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffff800010ae9104)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffff800010afada0)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (c0bd3e70)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (c0bdba18)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (c000000000bdf4c0)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (c000000000be8f84)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffe0006db4a2)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec7e0)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81843e58)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8184bec4)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff8180b4b8)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff818134e4)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff81893488)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff8189b4f4)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
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
In drivers/md/md.c (ffffffff818af084)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/md-bitmap.c (ffffffff818b7691)
Location: drivers/md/md.h:618
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
</details>
</li>
</ul>

## Differences
