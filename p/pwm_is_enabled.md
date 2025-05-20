# Function: <code>pwm_is_enabled</code>

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
In drivers/pwm/core.c (ffffffff8142c481)
Location: include/linux/pwm.h:110
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_set_polarity
  - drivers/pwm/core.c:pwm_seq_show
```
```
In drivers/pwm/sysfs.c (ffffffff8142d33d)
Location: include/linux/pwm.h:110
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:enable_show
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: include/linux/pwm.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527cd6)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81556f36)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81578576)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8161d6a6)
Location: include/linux/pwm.h:101
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff81643a6f)
Location: include/linux/pwm.h:101
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81643ef6)
Location: include/linux/pwm.h:101
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff8162688f)
Location: include/linux/pwm.h:106
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626ea3)
Location: include/linux/pwm.h:106
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff8169611f)
Location: include/linux/pwm.h:111
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696777)
Location: include/linux/pwm.h:111
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff817b6f8f)
Location: include/linux/pwm.h:111
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7624)
Location: include/linux/pwm.h:111
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff818d15cf)
Location: include/linux/pwm.h:108
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1d34)
Location: include/linux/pwm.h:108
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff819145bf)
Location: include/linux/pwm.h:108
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914d34)
Location: include/linux/pwm.h:108
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
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
In drivers/pwm/pwm-crc.c (ffffffff8195c52f)
Location: include/linux/pwm.h:104
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cca4)
Location: include/linux/pwm.h:104
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (ffff8000106da394)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (c0876b0c)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (c000000000851fc0)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (ffffffe0004b351c)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c2c6)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815867c6)
Location: include/linux/pwm.h:99
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
</details>
</li>
</ul>

## Differences
