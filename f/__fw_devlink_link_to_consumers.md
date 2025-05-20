# Function: <code>__fw_devlink_link_to_consumers</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff817ca260)
Location: drivers/base/core.c:1598
Inline: True
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817ca260-ffffffff817ca397: __fw_devlink_link_to_consumers.isra.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff817adb3c)
Location: drivers/base/core.c:1810
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_link_device
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
In drivers/base/core.c (ffffffff81837336)
Location: drivers/base/core.c:1851
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819793cf)
Location: drivers/base/core.c:1863
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff81ae5840)
Location: drivers/base/core.c:2133
Inline: True
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81ae5840-ffffffff81ae5934: __fw_devlink_link_to_consumers.isra.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81b33c10)
Location: drivers/base/core.c:2135
Inline: True
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81b33c10-ffffffff81b33d04: __fw_devlink_link_to_consumers.isra.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81b8b5a0)
Location: drivers/base/core.c:2150
Inline: True
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81b8b5a0-ffffffff81b8b694: __fw_devlink_link_to_consumers.isra.0 (STB_LOCAL)
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
