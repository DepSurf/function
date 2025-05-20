# Function: <code>dev_has_sync_state</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3164)
Location: include/linux/device.h:799
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
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
In drivers/base/core.c (ffffffff817c7a24)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
```
```
In drivers/base/dd.c (ffffffff817ce22e)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff817aaf34)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
```
```
In drivers/base/dd.c (ffffffff817b1d14)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff81834064)
Location: include/linux/device.h:790
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
```
```
In drivers/base/dd.c (ffffffff8183afcb)
Location: include/linux/device.h:790
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff81975974)
Location: include/linux/device.h:865
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
```
```
In drivers/base/dd.c (ffffffff8197d56b)
Location: include/linux/device.h:865
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff81ae17e4)
Location: include/linux/device.h:862
Inline: True
Inline callers:
  - drivers/base/core.c:__device_links_supplier_defer_sync
  - drivers/base/core.c:__device_links_supplier_defer_sync
```
```
In drivers/base/dd.c (ffffffff81aea98d)
Location: include/linux/device.h:862
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff81b310d4)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
```
In drivers/base/dd.c (ffffffff81b38cf5)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
In drivers/base/core.c (ffffffff81b886d4)
Location: include/linux/device.h:1022
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
```
In drivers/base/dd.c (ffffffff81b907b5)
Location: include/linux/device.h:1022
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
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
