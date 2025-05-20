# Function: <code>scsi_print_sense_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b87b0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_pr_command
```
**Symbols:**

```
ffffffff815b87b0-ffffffff815b87c8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81611030)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81611030-ffffffff81611048: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816408c0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816408c0-ffffffff816408d8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816552a0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816552a0-ffffffff816552b8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816be7f0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816be7f0-ffffffff816be808: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fadc0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816fadc0-ffffffff816fadd8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171d7f0)
Location: drivers/scsi/scsi_logging.c:405
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8171d7f0-ffffffff8171d808: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81758c30)
Location: drivers/scsi/scsi_logging.c:404
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81758c30-ffffffff81758c48: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8177cad0)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8177cad0-ffffffff8177cae8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8183fd90)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8183fd90-ffffffff8183fda8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff818503f0)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff818503f0-ffffffff81850408: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81833480)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81833480-ffffffff81833498: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff818bf4d0)
Location: drivers/scsi/scsi_logging.c:359
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff818bf4d0-ffffffff818bf4e8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0b940)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81a0b940-ffffffff81a0b964: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8bd20)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81b8bd20-ffffffff81b8bd44: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdfd20)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81bdfd20-ffffffff81bdfd44: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c34d20)
Location: drivers/scsi/scsi_logging.c:358
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81c34d20-ffffffff81c34d44: scsi_print_sense_hdr (STB_GLOBAL)
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
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff800010982ca8)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffff800010982ca8-ffff800010982cf0: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a556a0)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c0a556a0-c0a556c4: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3f4f0)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c000000000a3f4f0-c000000000a3f50c: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e84a4)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffe0005e84a4-ffffffe0005e84e0: scsi_print_sense_hdr (STB_GLOBAL)
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
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff817311c0)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff817311c0-ffffffff817311d8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8170a5e0)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8170a5e0-ffffffff8170a5f8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8176ff90)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8176ff90-ffffffff8176ffa8: scsi_print_sense_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_print_sense_hdr(const struct scsi_device *sdev, const char *name, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8178b730)
Location: drivers/scsi/scsi_logging.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8178b730-ffffffff8178b748: scsi_print_sense_hdr (STB_GLOBAL)
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
