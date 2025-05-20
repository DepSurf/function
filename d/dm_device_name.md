# Function: <code>dm_device_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a01c0)
Location: drivers/md/dm.c:2865
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_any_congested
```
**Symbols:**

```
ffffffff816a01c0-ffffffff816a01d2: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702cc5)
Location: drivers/md/dm.c:1868
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81701510-ffffffff81701522: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734b94)
Location: drivers/md/dm.c:1925
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81733270-ffffffff81733282: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174e13a)
Location: drivers/md/dm.c:2135
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8174c070-ffffffff8174c082: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c01a0)
Location: drivers/md/dm.c:2109
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff817be3f0-ffffffff817be402: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807fea)
Location: drivers/md/dm.c:2299
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff818066f0-ffffffff81806702: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8183402c)
Location: drivers/md/dm.c:2328
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81832820-ffffffff81832832: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875e40)
Location: drivers/md/dm.c:2359
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81875020-ffffffff81875032: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7c40)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818a6e30-ffffffff818a6e42: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81978496)
Location: drivers/md/dm.c:2366
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:clone_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81976d30-ffffffff81976d42: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197dc48)
Location: drivers/md/dm.c:2232
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:clone_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8197b910-ffffffff8197b922: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960388)
Location: drivers/md/dm.c:2251
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8195faf0-ffffffff8195fb02: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a08ae5)
Location: drivers/md/dm.c:2141
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81a07a60-ffffffff81a07a72: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b71e49)
Location: drivers/md/dm.c:2323
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81b6fa70-ffffffff81b6fa88: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0dc2d)
Location: drivers/md/dm.c:2425
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81d0c0b0-ffffffff81d0c0c8: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d7722d)
Location: drivers/md/dm.c:2461
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81d751f0-ffffffff81d75208: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2e45d)
Location: drivers/md/dm.c:2469
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:validate_hardware_zoned
  - drivers/md/dm-table.c:validate_hardware_zoned
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81e2c300-ffffffff81e2c318: dm_device_name (STB_GLOBAL)
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
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afe320)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffff800010afc020-ffff800010afc048: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd6d0)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
c0bdc508-c0bdc524: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bec1e0)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
c000000000bea090-c000000000bea0a0: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ee068)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffe0006ed25e-ffffffe0006ed282: dm_device_name (STB_GLOBAL)
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
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184dac0)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8184ccb0-ffffffff8184ccc2: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818150e0)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818142d0-ffffffff818142e2: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189d0f0)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8189c2e0-ffffffff8189c2f2: dm_device_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *dm_device_name(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b9450)
Location: drivers/md/dm.c:2363
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__split_and_process_non_flush
Direct callers:
  - drivers/md/dm-table.c:dm_table_device_name
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_table_add_target
  - drivers/md/dm-table.c:dm_put_device
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818b84a0-ffffffff818b84b2: dm_device_name (STB_GLOBAL)
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
