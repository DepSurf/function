# Function: <code>scsi_status_is_good</code>

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
In drivers/scsi/scsi_lib.c (ffffffff815af04b)
Location: include/scsi/scsi.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff815bad93)
Location: include/scsi/scsi.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff815c042a)
Location: include/scsi/scsi.h:69
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/scsi_lib.c (ffffffff816072e8)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff81616915)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff8161929e)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff816369b0)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff816463b3)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff81649f2e)
Location: include/scsi/scsi.h:50
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff81649489)
Location: include/scsi/scsi.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff8165af3b)
Location: include/scsi/scsi.h:40
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff8165e9f7)
Location: include/scsi/scsi.h:40
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff816b26a9)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff816c458b)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff816c7e0c)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff816ee85f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81700b64)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff817047b7)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff817123ff)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81723904)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
```
```
In drivers/scsi/sr.c (ffffffff81726c2e)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff8174dd6f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8175f27d)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81762361)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff81771f1f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff817831ba)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81786351)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int scsi_status_is_good(int status);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81836487)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/scsi/sd.c (ffffffff8184502c)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
Direct callers:
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8184a3fd)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff81841920-ffffffff81841940: scsi_status_is_good (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int scsi_status_is_good(int status);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81846f57)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/scsi/sd.c (ffffffff81855321)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
Direct callers:
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8185a8fd)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff81851e40-ffffffff81851e60: scsi_status_is_good (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int scsi_status_is_good(int status);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182a13f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/scsi/sd.c (ffffffff818393fb)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
Direct callers:
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8183d418)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff81834ec0-ffffffff81834eec: scsi_status_is_good (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool scsi_status_is_good(int status);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5902)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/scsi/sd.c (ffffffff818c5a15)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
Direct callers:
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff818c9f83)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff818c2680-ffffffff818c26bc: scsi_status_is_good (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool scsi_status_is_good(int status);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00e1d)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/scsi/sd.c (ffffffff81a124dc)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
Direct callers:
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81a17309)
Location: include/scsi/scsi.h:196
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff81a0f2d0-ffffffff81a0f320: scsi_status_is_good (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81b7f27d)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81b927d9)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81b98219)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff81bd322c)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff81be8cf4)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81bee7b6)
Location: include/scsi/scsi.h:197
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff81c27eac)
Location: include/scsi/scsi.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/sd.c (ffffffff81c3e254)
Location: include/scsi/scsi.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81c43e97)
Location: include/scsi/scsi.h:200
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffff8000109757d8)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffff800010989d00)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffff80001098ca54)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (c0a49c40)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (c0a5bf18)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (c0a5efe4)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (c000000000a2f5e4)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (c000000000a4a0d0)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (c000000000a4e094)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffe0005ddc5e)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffe0005edff2)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffe0005f157c)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff8172660f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff817378aa)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8173aa41)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff816ffa3f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8171954a)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8171c6e1)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff817653df)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8177803a)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff8177b1d1)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi_lib.c (ffffffff81780a6f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81791e5a)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sr.c (ffffffff81794d3f)
Location: include/scsi/scsi.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
