# Function: <code>dev_to_genpd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815afff1)
Location: drivers/base/power/domain.c:71
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
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
In drivers/base/power/domain.c (ffffffff815def21)
Location: drivers/base/power/domain.c:170
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
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
In drivers/base/power/domain.c (ffffffff815f3b31)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
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
In drivers/base/power/domain.c (ffffffff8165b961)
Location: drivers/base/power/domain.c:177
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
In drivers/base/power/domain.c (ffffffff81697631)
Location: drivers/base/power/domain.c:178
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
In drivers/base/power/domain.c (ffffffff816b8311)
Location: drivers/base/power/domain.c:178
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
In drivers/base/power/domain.c (ffffffff816f2061)
Location: drivers/base/power/domain.c:181
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
In drivers/base/power/domain.c (ffffffff817167e1)
Location: drivers/base/power/domain.c:176
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
In drivers/base/power/domain.c (ffffffff817d02e6)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff817e4956)
Location: drivers/base/power/domain.c:177
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff817c8d56)
Location: drivers/base/power/domain.c:177
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff81853273)
Location: drivers/base/power/domain.c:177
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff81999443)
Location: drivers/base/power/domain.c:180
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff81b0a743)
Location: drivers/base/power/domain.c:180
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
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
In drivers/base/power/domain.c (ffffffff81b58763)
Location: drivers/base/power/domain.c:180
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
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
In drivers/pmdomain/core.c (ffffffff81aa0123)
Location: drivers/pmdomain/core.c:179
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_complete
  - drivers/pmdomain/core.c:genpd_finish_resume
  - drivers/pmdomain/core.c:genpd_finish_suspend
  - drivers/pmdomain/core.c:genpd_prepare
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:genpd_dev_pm_qos_notifier
  - drivers/pmdomain/core.c:genpd_dev_pm_start
  - drivers/pmdomain/core.c:genpd_dev_pm_set_performance_state
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
In drivers/base/power/domain.c (ffff800010905efc)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
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
In drivers/base/power/domain.c (c09efc60)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
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
In drivers/base/power/domain.c (c0000000009a4bd0)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
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
In drivers/base/power/domain.c (ffffffe00058d590)
Location: drivers/base/power/domain.c:176
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
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
In drivers/base/power/domain.c (ffffffff816dcb11)
Location: drivers/base/power/domain.c:176
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
In drivers/base/power/domain.c (ffffffff816b7191)
Location: drivers/base/power/domain.c:176
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
In drivers/base/power/domain.c (ffffffff8170a4a1)
Location: drivers/base/power/domain.c:176
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
In drivers/base/power/domain.c (ffffffff817251a1)
Location: drivers/base/power/domain.c:176
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
```
</details>
</li>
</ul>

## Differences
