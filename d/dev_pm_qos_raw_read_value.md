# Function: <code>dev_pm_qos_raw_read_value</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815eac4b)
Location: include/linux/pm_qos.h:174
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8176ff1f)
Location: include/linux/pm_qos.h:174
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In drivers/base/power/qos.c (ffffffff81651ffb)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
```
```
In drivers/cpuidle/governors/ladder.c (ffffffff817e55ed)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff817e583e)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In drivers/base/power/qos.c (ffffffff8168d8db)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
```
```
In drivers/cpuidle/governor.c (ffffffff8182ddca)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
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
In drivers/base/power/qos.c (ffffffff816adb2b)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
```
```
In drivers/cpuidle/governor.c (ffffffff81859f8a)
Location: include/linux/pm_qos.h:177
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
</details>
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
