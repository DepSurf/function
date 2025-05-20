# Function: <code>dm_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a0200)
Location: drivers/md/dm.c:3432
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-sysfs.c:dm_sysfs_init
```
**Symbols:**

```
ffffffff816a0200-ffffffff816a0212: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701550)
Location: drivers/md/dm.c:2435
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81701550-ffffffff81701562: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817332b0)
Location: drivers/md/dm.c:2495
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff817332b0-ffffffff817332c2: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174c0b0)
Location: drivers/md/dm.c:2707
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8174c0b0-ffffffff8174c0c2: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bfe51)
Location: drivers/md/dm.c:2682
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff817be430-ffffffff817be442: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81809189)
Location: drivers/md/dm.c:2871
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81806730-ffffffff81806742: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818352d9)
Location: drivers/md/dm.c:2894
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81832860-ffffffff81832872: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81877c98)
Location: drivers/md/dm.c:2925
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81875060-ffffffff81875072: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a9ab8)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff818a6e70-ffffffff818a6e82: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979d18)
Location: drivers/md/dm.c:2982
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81976d70-ffffffff81976d82: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197e628)
Location: drivers/md/dm.c:2829
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8197b950-ffffffff8197b962: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81962478)
Location: drivers/md/dm.c:2848
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8195fb30-ffffffff8195fb42: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0962c)
Location: drivers/md/dm.c:2737
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81a07aa0-ffffffff81a07ab2: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b716b9)
Location: drivers/md/dm.c:2918
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
Direct callers:
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81b6fab0-ffffffff81b6fac8: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0e509)
Location: drivers/md/dm.c:3023
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
Direct callers:
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81d0c110-ffffffff81d0c128: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d77b09)
Location: drivers/md/dm.c:3066
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
Direct callers:
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81d75250-ffffffff81d75268: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2ed39)
Location: drivers/md/dm.c:3074
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
Direct callers:
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81e2c360-ffffffff81e2c378: dm_disk (STB_GLOBAL)
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
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afe0a4)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffff800010afc048-ffff800010afc070: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd23c)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c0bdc558-c0bdc574: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebbdc)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c000000000bea0c0-c000000000bea0d0: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006edc62)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffe0006ed2ac-ffffffe0006ed2ce: dm_disk (STB_GLOBAL)
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
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184f938)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8184ccf0-ffffffff8184cd02: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81816f48)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81814310-ffffffff81814322: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189ef68)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8189c320-ffffffff8189c332: dm_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *dm_disk(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bb653)
Location: drivers/md/dm.c:2930
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff818b84e0-ffffffff818b84f2: dm_disk (STB_GLOBAL)
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
