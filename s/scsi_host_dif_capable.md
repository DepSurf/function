# Function: <code>scsi_host_dif_capable</code>

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
In drivers/scsi/sd.c (ffffffff815bba31)
Location: include/scsi/scsi_host.h:876
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf5f4)
Location: include/scsi/scsi_host.h:876
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff8161622b)
Location: include/scsi/scsi_host.h:871
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81617da4)
Location: include/scsi/scsi_host.h:871
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81646045)
Location: include/scsi/scsi_host.h:879
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81647944)
Location: include/scsi/scsi_host.h:879
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81659bf5)
Location: include/scsi/scsi_host.h:869
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c514)
Location: include/scsi/scsi_host.h:869
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff816c2e30)
Location: include/scsi/scsi_host.h:864
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5b84)
Location: include/scsi/scsi_host.h:864
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff816ff0eb)
Location: include/scsi/scsi_host.h:840
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81702117)
Location: include/scsi/scsi_host.h:840
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81721f93)
Location: include/scsi/scsi_host.h:819
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff817250d7)
Location: include/scsi/scsi_host.h:819
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff8175e2bf)
Location: include/scsi/scsi_host.h:812
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81760737)
Location: include/scsi/scsi_host.h:812
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff817822d0)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff817846d7)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81843a48)
Location: include/scsi/scsi_host.h:825
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff818481e7)
Location: include/scsi/scsi_host.h:825
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81853d78)
Location: include/scsi/scsi_host.h:832
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81858737)
Location: include/scsi/scsi_host.h:832
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81837783)
Location: include/scsi/scsi_host.h:848
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff8183b6b7)
Location: include/scsi/scsi_host.h:848
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff818c2b99)
Location: include/scsi/scsi_host.h:849
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff818c7e71)
Location: include/scsi/scsi_host.h:849
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81a11304)
Location: include/scsi/scsi_host.h:831
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81a14cd0)
Location: include/scsi/scsi_host.h:831
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81b91593)
Location: include/scsi/scsi_host.h:840
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81b95190)
Location: include/scsi/scsi_host.h:840
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81be7aa5)
Location: include/scsi/scsi_host.h:846
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81beb700)
Location: include/scsi/scsi_host.h:846
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81c3ce1f)
Location: include/scsi/scsi_host.h:849
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81c40dc0)
Location: include/scsi/scsi_host.h:849
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffff800010988fb4)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffff80001098aeb8)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (c0a5af28)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (c0a5d1b0)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (c000000000a48f74)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (c000000000a4b92c)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffe0005ed1f8)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffe0005ef2ce)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff817369c0)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81738dc7)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81718660)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff8171aa67)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81777150)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81779557)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
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
In drivers/scsi/sd.c (ffffffff81790f70)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81793387)
Location: include/scsi/scsi_host.h:824
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
</ul>

## Differences
