# Function: <code>dev_is_best_effort</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool dev_is_best_effort(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1054
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
```
**Symbols:**

```
ffffffff81ae11e0-ffffffff81ae1236: dev_is_best_effort (STB_LOCAL)
ffffffff820982c4-ffffffff820982df: dev_is_best_effort.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool dev_is_best_effort(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:996
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
```
**Symbols:**

```
ffffffff81b2f430-ffffffff81b2f486: dev_is_best_effort (STB_LOCAL)
ffffffff821192f0-ffffffff8211930b: dev_is_best_effort.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dev_is_best_effort(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:999
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
```
**Symbols:**

```
ffffffff81b86c30-ffffffff81b86c86: dev_is_best_effort (STB_LOCAL)
ffffffff821f72b3-ffffffff821f72ce: dev_is_best_effort.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
