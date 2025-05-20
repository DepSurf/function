# Function: <code>mddev_is_clustered</code>

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
In drivers/md/md.c (ffffffff81691981)
Location: drivers/md/md.h:698
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/bitmap.c (ffffffff8169c436)
Location: drivers/md/md.h:698
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_resize
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
In drivers/md/md.c (ffffffff816f32cb)
Location: drivers/md/md.h:676
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/bitmap.c (ffffffff816ff202)
Location: drivers/md/md.h:676
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff817249cb)
Location: drivers/md/md.h:702
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/bitmap.c (ffffffff81730e41)
Location: drivers/md/md.h:702
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff8173c8c5)
Location: drivers/md/md.h:709
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/bitmap.c (ffffffff81749db0)
Location: drivers/md/md.h:709
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff817ae496)
Location: drivers/md/md.h:716
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff817bc090)
Location: drivers/md/md.h:716
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff817f8a9b)
Location: drivers/md/md.h:735
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8180412b)
Location: drivers/md/md.h:735
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81826ec5)
Location: drivers/md/md.h:737
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8183032b)
Location: drivers/md/md.h:737
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff8186935d)
Location: drivers/md/md.h:748
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81872a80)
Location: drivers/md/md.h:748
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff8189b0fd)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818a4880)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff8196a65a)
Location: drivers/md/md.h:779
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81974365)
Location: drivers/md/md.h:779
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff819711da)
Location: drivers/md/md.h:781
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81979265)
Location: drivers/md/md.h:781
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff819552ca)
Location: drivers/md/md.h:780
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8195d723)
Location: drivers/md/md.h:780
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff819fa8fa)
Location: drivers/md/md.h:788
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81a02fbd)
Location: drivers/md/md.h:788
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81b61dea)
Location: drivers/md/md.h:796
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81b6abd6)
Location: drivers/md/md.h:796
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81cfbfde)
Location: drivers/md/md.h:813
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d069fb)
Location: drivers/md/md.h:813
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81d63bfe)
Location: drivers/md/md.h:830
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d6fcc9)
Location: drivers/md/md.h:830
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81e1ab61)
Location: drivers/md/md.h:808
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81e26dc1)
Location: drivers/md/md.h:808
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:filemap_write_page
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
In drivers/md/md.c (ffff800010aef4b8)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffff800010af8f78)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (c0bd09fc)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (c0bd9e8c)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (c000000000bdad64)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (c000000000be7088)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffe0006e39e4)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb17c)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff81840f7d)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8184a700)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff818085dd)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81811d30)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff818905ad)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81899d30)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
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
In drivers/md/md.c (ffffffff818ac19d)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:update_size
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:safe_delay_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818b5ea0)
Location: drivers/md/md.h:768
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
```
</details>
</li>
</ul>

## Differences
