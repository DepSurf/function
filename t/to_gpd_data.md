# Function: <code>to_gpd_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:109
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:109
Inline: True
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:123
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:123
Inline: True
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:125
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:125
Inline: True
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:132
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:132
Inline: True
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
In drivers/base/power/domain.c (ffffffff81698874)
Location: include/linux/pm_domain.h:136
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81698c41)
Location: include/linux/pm_domain.h:136
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff816b90c4)
Location: include/linux/pm_domain.h:167
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816b94a3)
Location: include/linux/pm_domain.h:167
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff816f30ea)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816f3623)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff8171756e)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81717a23)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff817d265f)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817d365f)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:__default_power_down_ok
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff817e75af)
Location: include/linux/pm_domain.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817e80be)
Location: include/linux/pm_domain.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:__default_power_down_ok
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff817c9d68)
Location: include/linux/pm_domain.h:206
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817cc470)
Location: include/linux/pm_domain.h:206
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff81854290)
Location: include/linux/pm_domain.h:208
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
  - drivers/base/power/domain.c:_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81856b9d)
Location: include/linux/pm_domain.h:208
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:212
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:212
Inline: True
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:214
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:214
Inline: True
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
In drivers/base/power/domain.c (0)
Location: include/linux/pm_domain.h:215
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:215
Inline: True
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
In drivers/pmdomain/core.c (0)
Location: include/linux/pm_domain.h:217
Inline: True
```
```
In drivers/pmdomain/governor.c (0)
Location: include/linux/pm_domain.h:217
Inline: True
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
In drivers/base/power/domain.c (ffff800010909abc)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffff80001090ad24)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (c09f17e8)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (c09f3fa4)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (c0000000009a907c)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (c0000000009aade4)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffe00058facc)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffe000590662)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff816dd89e)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816ddd53)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff816b7f0e)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816b83b3)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff8170b22e)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff8170b6e3)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
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
In drivers/base/power/domain.c (ffffffff81724cde)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817260d3)
Location: include/linux/pm_domain.h:187
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
</details>
</li>
</ul>

## Differences
