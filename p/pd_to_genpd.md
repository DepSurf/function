# Function: <code>pd_to_genpd</code>

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
Location: include/linux/pm_domain.h:77
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:77
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
Location: include/linux/pm_domain.h:91
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:91
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
Location: include/linux/pm_domain.h:92
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:92
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
Location: include/linux/pm_domain.h:98
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:98
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
In drivers/base/power/domain.c (ffffffff8169763f)
Location: include/linux/pm_domain.h:102
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81698db5)
Location: include/linux/pm_domain.h:102
Inline: True
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
In drivers/base/power/domain.c (ffffffff816b831f)
Location: include/linux/pm_domain.h:129
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816b9615)
Location: include/linux/pm_domain.h:129
Inline: True
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
In drivers/base/power/domain.c (ffffffff816f206f)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816f381c)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff81717549)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81717c1c)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff817d27ee)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817d35b5)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:__default_power_down_ok
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
In drivers/base/power/domain.c (ffffffff817e7589)
Location: include/linux/pm_domain.h:158
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817e8015)
Location: include/linux/pm_domain.h:158
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:__default_power_down_ok
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
In drivers/base/power/domain.c (ffffffff817cb499)
Location: include/linux/pm_domain.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817cc914)
Location: include/linux/pm_domain.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
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
In drivers/base/power/domain.c (ffffffff818554b9)
Location: include/linux/pm_domain.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff81856ef4)
Location: include/linux/pm_domain.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
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
In drivers/base/power/domain.c (ffffffff8199c230)
Location: include/linux/pm_domain.h:169
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:169
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
In drivers/base/power/domain.c (ffffffff81b0d3f0)
Location: include/linux/pm_domain.h:171
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:171
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
In drivers/base/power/domain.c (ffffffff81b5b4a0)
Location: include/linux/pm_domain.h:172
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_synced_poweroff
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/pm_domain.h:172
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
In drivers/pmdomain/core.c (ffffffff81aa2fa0)
Location: include/linux/pm_domain.h:174
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_add_notifier
  - drivers/pmdomain/core.c:pm_genpd_remove_device
  - drivers/pmdomain/core.c:genpd_switch_state
  - drivers/pmdomain/core.c:genpd_complete
  - drivers/pmdomain/core.c:genpd_finish_resume
  - drivers/pmdomain/core.c:genpd_finish_suspend
  - drivers/pmdomain/core.c:genpd_prepare
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:genpd_dev_pm_qos_notifier
  - drivers/pmdomain/core.c:genpd_dev_pm_start
  - drivers/pmdomain/core.c:dev_pm_genpd_synced_poweroff
  - drivers/pmdomain/core.c:dev_pm_genpd_get_next_hrtimer
  - drivers/pmdomain/core.c:dev_pm_genpd_set_next_wakeup
  - drivers/pmdomain/core.c:dev_pm_genpd_set_performance_state
  - drivers/pmdomain/core.c:genpd_dev_pm_set_performance_state
```
```
In drivers/pmdomain/governor.c (0)
Location: include/linux/pm_domain.h:174
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
In drivers/base/power/domain.c (ffff800010905f08)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffff80001090aa44)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (c09efc74)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (c09f4234)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (c0000000009a4be8)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (c0000000009ab0a0)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffe00058d59c)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffe0005907b6)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff816dd879)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816ddf4c)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff816b7ee9)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff816b85ac)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff8170b209)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff8170b8dc)
Location: include/linux/pm_domain.h:148
Inline: True
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
In drivers/base/power/domain.c (ffffffff81724cb9)
Location: include/linux/pm_domain.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/base/power/domain_governor.c (ffffffff817262cc)
Location: include/linux/pm_domain.h:148
Inline: True
```
</details>
</li>
</ul>

## Differences
