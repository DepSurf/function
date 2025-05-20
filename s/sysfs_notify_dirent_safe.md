# Function: <code>sysfs_notify_dirent_safe</code>

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
In drivers/md/md.c (ffffffff8168dd42)
Location: drivers/md/md.h:555
Inline: True
Inline callers:
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:action_store
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/bitmap.c (ffffffff8169d142)
Location: drivers/md/md.h:555
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff816f2220)
Location: drivers/md/md.h:532
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
```
In drivers/md/bitmap.c (ffffffff816fe422)
Location: drivers/md/md.h:532
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff81721985)
Location: drivers/md/md.h:558
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
```
In drivers/md/bitmap.c (ffffffff81730082)
Location: drivers/md/md.h:558
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff8173b862)
Location: drivers/md/md.h:571
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/bitmap.c (ffffffff81749b72)
Location: drivers/md/md.h:571
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff817aba12)
Location: drivers/md/md.h:577
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff817bbe52)
Location: drivers/md/md.h:577
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff817f3735)
Location: drivers/md/md.h:594
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81803742)
Location: drivers/md/md.h:594
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_endwrite
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
In drivers/md/md.c (ffffffff8181f715)
Location: drivers/md/md.h:596
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8182ff32)
Location: drivers/md/md.h:596
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff818609a6)
Location: drivers/md/md.h:605
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81872669)
Location: drivers/md/md.h:605
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff818925d6)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818a4469)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81963046)
Location: drivers/md/md.h:621
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81973804)
Location: drivers/md/md.h:621
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff8196a81c)
Location: drivers/md/md.h:624
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81978704)
Location: drivers/md/md.h:624
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff8194e62c)
Location: drivers/md/md.h:623
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8195d4e4)
Location: drivers/md/md.h:623
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff819f3a2f)
Location: drivers/md/md.h:624
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81a02d44)
Location: drivers/md/md.h:624
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81b5d732)
Location: drivers/md/md.h:632
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81b6a6a5)
Location: drivers/md/md.h:632
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81cf7625)
Location: drivers/md/md.h:649
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d064e5)
Location: drivers/md/md.h:649
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81d5ef1d)
Location: drivers/md/md.h:671
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d6f565)
Location: drivers/md/md.h:671
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81e1618d)
Location: drivers/md/md.h:652
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81e26845)
Location: drivers/md/md.h:652
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffff800010ae8d48)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffff800010af7e00)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (c0bcc498)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (c0bd76dc)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (c000000000bcda68)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (c000000000be6d40)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffe0006dadd4)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffe0006ead3c)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81838456)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8184a2e9)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff817ffac6)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81811929)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff81887a86)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81899919)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/md/md.c (ffffffff818a3db6)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818b5459)
Location: drivers/md/md.h:612
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
</details>
</li>
</ul>

## Differences
