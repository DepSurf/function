# Function: <code>dm_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a01e0)
Location: drivers/md/dm.c:2928
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:rq_completed
Direct callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
```
**Symbols:**

```
ffffffff816a01e0-ffffffff816a01f2: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701bee)
Location: drivers/md/dm.c:1931
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81701530-ffffffff81701542: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8173393e)
Location: drivers/md/dm.c:1991
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81733290-ffffffff817332a2: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174cb8e)
Location: drivers/md/dm.c:2201
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8174c090-ffffffff8174c0a2: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bed6e)
Location: drivers/md/dm.c:2175
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff817be410-ffffffff817be422: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81808f6e)
Location: drivers/md/dm.c:2364
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81806710-ffffffff81806722: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818350ce)
Location: drivers/md/dm.c:2390
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81832840-ffffffff81832852: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876ef2)
Location: drivers/md/dm.c:2421
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81875040-ffffffff81875052: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a98ae)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff818a6e50-ffffffff818a6e62: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979ade)
Location: drivers/md/dm.c:2430
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81976d50-ffffffff81976d62: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197e42b)
Location: drivers/md/dm.c:2296
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8197b930-ffffffff8197b942: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8196225b)
Location: drivers/md/dm.c:2315
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8195fb10-ffffffff8195fb22: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0939b)
Location: drivers/md/dm.c:2204
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81a07a80-ffffffff81a07a92: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b7027b)
Location: drivers/md/dm.c:2386
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81b6fa90-ffffffff81b6faa8: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0c9db)
Location: drivers/md/dm.c:2488
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81d0c0e0-ffffffff81d0c0f8: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d7594b)
Location: drivers/md/dm.c:2524
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81d75220-ffffffff81d75238: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2ca4b)
Location: drivers/md/dm.c:2532
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81e2c330-ffffffff81e2c348: dm_put (STB_GLOBAL)
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
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afdd1c)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffff800010afcbf8-ffff800010afcc4c: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdc8d8)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
c0bdc524-c0bdc558: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bea7f0)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
c000000000bea0a0-c000000000bea0c0: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef976)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffe0006ed282-ffffffe0006ed2ac: dm_put (STB_GLOBAL)
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
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184f72e)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8184ccd0-ffffffff8184cce2: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81816d3e)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff818142f0-ffffffff81814302: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189ed5e)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8189c300-ffffffff8189c312: dm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dm_put(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b86ee)
Location: drivers/md/dm.c:2426
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_attr_store
  - drivers/md/dm-sysfs.c:dm_attr_show
  - drivers/md/dm-rq.c:rq_completed
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff818b84c0-ffffffff818b84d2: dm_put (STB_GLOBAL)
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
