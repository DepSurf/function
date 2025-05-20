# Function: <code>regulator_get_suspend_state</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81608cfc)
Location: drivers/regulator/core.c:380
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_resume_early
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff816254fd)
Location: drivers/regulator/core.c:564
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff81657e5d)
Location: drivers/regulator/core.c:546
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff8167bd7d)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff8172a08d)
Location: drivers/regulator/core.c:553
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81746e7d)
Location: drivers/regulator/core.c:552
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
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
In drivers/regulator/core.c (ffffffff8172a82d)
Location: drivers/regulator/core.c:553
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
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
In drivers/regulator/core.c (ffffffff817aaead)
Location: drivers/regulator/core.c:543
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
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
In drivers/regulator/core.c (ffffffff818e5aed)
Location: drivers/regulator/core.c:544
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_get_suspend_state_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3a17d)
Location: drivers/regulator/core.c:544
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_get_suspend_state_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a83d5d)
Location: drivers/regulator/core.c:610
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_get_suspend_state_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad650d)
Location: drivers/regulator/core.c:612
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_get_suspend_state_check
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
In drivers/regulator/core.c (ffff800010844f64)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (c094effc)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (c0000000008e1180)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffe000521188)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff816445fb)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81621c5d)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff8166fbbd)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
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
In drivers/regulator/core.c (ffffffff8168a21d)
Location: drivers/regulator/core.c:550
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_suspend_enable
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:suspend_set_state
```
</details>
</li>
</ul>

## Differences
