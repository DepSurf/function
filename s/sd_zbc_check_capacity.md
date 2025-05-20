# Function: <code>sd_zbc_check_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81648b5f)
Location: drivers/scsi/sd_zbc.c:407
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8165d48e)
Location: drivers/scsi/sd_zbc.c:395
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff816c6af4)
Location: drivers/scsi/sd_zbc.c:450
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81702eeb)
Location: drivers/scsi/sd_zbc.c:357
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_zbc_check_capacity(struct scsi_disk *sdkp, unsigned char *buf, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848740)
Location: drivers/scsi/sd_zbc.c:595
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81848740-ffffffff81848897: sd_zbc_check_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_check_capacity(struct scsi_disk *sdkp, unsigned char *buf, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81858c30)
Location: drivers/scsi/sd_zbc.c:596
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81858c30-ffffffff81858d80: sd_zbc_check_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183ca6f)
Location: drivers/scsi/sd_zbc.c:599
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818c93df)
Location: drivers/scsi/sd_zbc.c:598
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:706
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81a151e0-ffffffff81a153d1: sd_zbc_check_capacity.constprop.0 (STB_LOCAL)
ffffffff81ed5e4a-ffffffff81ed5e75: sd_zbc_check_capacity.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:712
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81b95e60-ffffffff81b96051: sd_zbc_check_capacity.constprop.0 (STB_LOCAL)
ffffffff8209bfbf-ffffffff8209bfea: sd_zbc_check_capacity.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:714
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81bec420-ffffffff81bec60e: sd_zbc_check_capacity.constprop.0 (STB_LOCAL)
ffffffff8211cf20-ffffffff8211cf45: sd_zbc_check_capacity.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:714
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81c41ae0-ffffffff81c41cce: sd_zbc_check_capacity.constprop.0 (STB_LOCAL)
ffffffff821fae38-ffffffff821fae5d: sd_zbc_check_capacity.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
