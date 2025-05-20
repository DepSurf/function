# Function: <code>dm_suspended_md</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a0343)
Location: drivers/md/dm.c:3457
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_resume
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff816a4990-ffffffff816a49a8: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702671)
Location: drivers/md/dm.c:2460
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81704b40-ffffffff81704b58: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734531)
Location: drivers/md/dm.c:2520
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff817369f0-ffffffff81736a08: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d8f1)
Location: drivers/md/dm.c:2732
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff8174fe20-ffffffff8174fe38: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf9e1)
Location: drivers/md/dm.c:2711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff817c2000-ffffffff817c2015: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807a61)
Location: drivers/md/dm.c:2900
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff8180a760-ffffffff8180a775: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833931)
Location: drivers/md/dm.c:2923
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81836760-ffffffff81836775: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875871)
Location: drivers/md/dm.c:2954
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81879320-ffffffff81879335: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7621)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff818ab160-ffffffff818ab175: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977391)
Location: drivers/md/dm.c:3011
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff8197b330-ffffffff8197b345: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b97c)
Location: drivers/md/dm.c:2858
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff8197fb50-ffffffff8197fb65: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8195fb5c)
Location: drivers/md/dm.c:2877
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81963cd0-ffffffff81963ce5: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a07acc)
Location: drivers/md/dm.c:2766
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81a0bc80-ffffffff81a0bc95: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b6fadc)
Location: drivers/md/dm.c:2947
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81b74170-ffffffff81b7418b: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0c56c)
Location: drivers/md/dm.c:3052
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81d11150-ffffffff81d1116b: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d7575c)
Location: drivers/md/dm.c:3095
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81d7a5e0-ffffffff81d7a5fb: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2c85c)
Location: drivers/md/dm.c:3103
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81e31780-ffffffff81e3179b: dm_suspended_md (STB_GLOBAL)
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
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc4b8)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffff800010b013e8-ffff800010b01414: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd320)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
c0be0ba0-c0be0bc0: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebd58)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
c000000000bf0750-c000000000bf0764: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006edd22)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffe0006f13e0-ffffffe0006f1406: dm_suspended_md (STB_GLOBAL)
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
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184d4a1)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff81850fe0-ffffffff81850ff5: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814ac1)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff818185f0-ffffffff81818605: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189cad1)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff818a0610-ffffffff818a0625: dm_suspended_md (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dm_suspended_md(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b8e31)
Location: drivers/md/dm.c:2959
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspended
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-sysfs.c:dm_attr_suspended_show
```
**Symbols:**

```
ffffffff818bc850-ffffffff818bc865: dm_suspended_md (STB_GLOBAL)
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
