# Function: <code>device_pm_not_required</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/sysfs.c (ffffffff816e6045)
Location: include/linux/device.h:1191
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff816ee7e5)
Location: include/linux/device.h:1191
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff8170a415)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff817127c5)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff817c53f5)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff817cdfe5)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff817d9f05)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff817e28f5)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff817be2c5)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff817c6cd5)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff81848645)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff818510b5)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff8198d365)
Location: include/linux/device.h:806
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81996bb5)
Location: include/linux/device.h:806
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff81afd0b5)
Location: include/linux/device.h:803
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81b07985)
Location: include/linux/device.h:803
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff81b4b4a5)
Location: include/linux/device.h:929
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81b559d5)
Location: include/linux/device.h:929
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff81ba3895)
Location: include/linux/device.h:961
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81badf95)
Location: include/linux/device.h:961
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffff8000108f8888)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffff8000109033c8)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (c09e4384)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (c09ed790)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (c000000000994730)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (c0000000009a1bb0)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffe000588b50)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
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
In drivers/base/power/sysfs.c (ffffffff816cfb65)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff816d8b45)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff816aae95)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff816b3185)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff816fe0d5)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81706485)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
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
In drivers/base/power/sysfs.c (ffffffff81718925)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/base/power/main.c (ffffffff81720e95)
Location: include/linux/device.h:1433
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
</details>
</li>
</ul>

## Differences
