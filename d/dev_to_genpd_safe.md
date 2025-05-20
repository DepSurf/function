# Function: <code>dev_to_genpd_safe</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817174f5)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff817d27b5)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff817e7525)
Location: drivers/base/power/domain.c:161
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff817cb435)
Location: drivers/base/power/domain.c:161
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff81855455)
Location: drivers/base/power/domain.c:161
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff8199c1c5)
Location: drivers/base/power/domain.c:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff81b0d385)
Location: drivers/base/power/domain.c:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff81b5b435)
Location: drivers/base/power/domain.c:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:dev_pm_genpd_synced_poweroff
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/pmdomain/core.c (ffffffff81aa2f35)
Location: drivers/pmdomain/core.c:163
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_add_notifier
  - drivers/pmdomain/core.c:pm_genpd_remove_device
  - drivers/pmdomain/core.c:genpd_switch_state
  - drivers/pmdomain/core.c:dev_pm_genpd_synced_poweroff
  - drivers/pmdomain/core.c:dev_pm_genpd_get_next_hrtimer
  - drivers/pmdomain/core.c:dev_pm_genpd_set_next_wakeup
  - drivers/pmdomain/core.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffff800010909be8)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (c09f18fc)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (c0000000009a9200)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffe00058fbc2)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff816dd825)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff816b7e95)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff8170b1b5)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
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
In drivers/base/power/domain.c (ffffffff81724c65)
Location: drivers/base/power/domain.c:160
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
</details>
</li>
</ul>

## Differences
