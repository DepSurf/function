# Function: <code>blk_set_cmd_filter_defaults</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81f9b6f9)
Location: block/scsi_ioctl.c:127
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81fc6a97)
Location: block/scsi_ioctl.c:127
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff820034df)
Location: block/scsi_ioctl.c:127
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff820e6dd9)
Location: block/scsi_ioctl.c:127
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff826efb54)
Location: block/scsi_ioctl.c:127
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff82719faa)
Location: block/scsi_ioctl.c:124
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff828d1fa3)
Location: block/scsi_ioctl.c:124
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff828ebf95)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff828f4b64)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81568091)
Location: block/scsi_ioctl.c:112
Inline: True
Direct callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
**Symbols:**

```
ffffffff81568091-ffffffff81568447: blk_set_cmd_filter_defaults.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81bf372d)
Location: block/scsi_ioctl.c:110
Inline: True
Direct callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
**Symbols:**

```
ffffffff81bf372d-ffffffff81bf3ae3: blk_set_cmd_filter_defaults.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81be569a)
Location: block/scsi_ioctl.c:110
Inline: True
Direct callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
**Symbols:**

```
ffffffff81be569a-ffffffff81be5943: blk_set_cmd_filter_defaults.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/scsi_ioctl.c (ffff80001146f000)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (c1547f64)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (c00000000139f000)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffe0000295a6)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff828dda18)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff828d6134)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff828f078c)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
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
In block/scsi_ioctl.c (ffffffff828f5bb8)
Location: block/scsi_ioctl.c:110
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
</details>
</li>
</ul>

## Differences
