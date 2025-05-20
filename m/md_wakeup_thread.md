# Function: <code>md_wakeup_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168dc80)
Location: drivers/md/md.c:7121
Inline: False
Direct callers:
  - drivers/md/md.c:md_unplug
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/bitmap.c:timeout_store
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:location_store
```
**Symbols:**

```
ffffffff8168dc80-ffffffff8168dcd9: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816ef1e0)
Location: drivers/md/md.c:7161
Inline: False
Direct callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_unplug
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/bitmap.c:timeout_store
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff816ef1e0-ffffffff816ef235: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817205c0)
Location: drivers/md/md.c:7218
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_unplug
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/bitmap.c:timeout_store
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff817205c0-ffffffff81720615: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173ad70)
Location: drivers/md/md.c:7439
Inline: True
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/bitmap.c:timeout_store
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff8173ad70-ffffffff8173adc9: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817aa010)
Location: drivers/md/md.c:7494
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817aa010-ffffffff817aa066: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f34e0)
Location: drivers/md/md.c:7563
Inline: True
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817f34e0-ffffffff817f3535: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181f4c0)
Location: drivers/md/md.c:7550
Inline: True
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8181f4c0-ffffffff8181f515: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81860150)
Location: drivers/md/md.c:7612
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81860150-ffffffff818601a5: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81891d80)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81891d80-ffffffff81891dd5: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81962ec0)
Location: drivers/md/md.c:7914
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81962ec0-ffffffff81962f18: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81969760)
Location: drivers/md/md.c:7942
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81969760-ffffffff819697b8: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194d660)
Location: drivers/md/md.c:7896
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff8194d660-ffffffff8194d6b8: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f2a70)
Location: drivers/md/md.c:7909
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff819f2a70-ffffffff819f2ac5: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b574d0)
Location: drivers/md/md.c:7906
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81b574d0-ffffffff81b57541: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf09d0)
Location: drivers/md/md.c:7896
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81cf09d0-ffffffff81cf0a41: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d595f0)
Location: drivers/md/md.c:7904
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81d595f0-ffffffff81d59665: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e10460)
Location: drivers/md/md.c:8036
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:__mddev_resume
  - drivers/md/md.c:__mddev_resume
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81e10460-ffffffff81e104d5: md_wakeup_thread (STB_GLOBAL)
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
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae82a8)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffff800010ae82a8-ffff800010ae832c: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc5494)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c0bc5494-c0bc5500: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bccef0)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c000000000bccef0-c000000000bccf84: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006da0dc)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffe0006da0dc-ffffffe0006da144: md_wakeup_thread (STB_GLOBAL)
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
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81837c00)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81837c00-ffffffff81837c55: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817ff270)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817ff270-ffffffff817ff2c5: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81887230)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81887230-ffffffff81887285: md_wakeup_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a3460)
Location: drivers/md/md.c:7716
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md-bitmap.c:timeout_store
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff818a3460-ffffffff818a34b5: md_wakeup_thread (STB_GLOBAL)
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
