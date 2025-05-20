# Function: <code>update_pm_runtime_accounting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81556938)
Location: drivers/base/power/runtime.c:63
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
Direct callers:
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
```
**Symbols:**

```
ffffffff81557db0-ffffffff81557df7: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9671)
Location: drivers/base/power/runtime.c:63
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
Direct callers:
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
```
**Symbols:**

```
ffffffff815a9e60-ffffffff815a9ea7: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8341)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
Direct callers:
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
```
**Symbols:**

```
ffffffff815d8870-ffffffff815d88b7: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ec9a0)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
Direct callers:
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
```
**Symbols:**

```
ffffffff815ed380-ffffffff815ed3c5: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81653d5e)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
Direct callers:
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
```
**Symbols:**

```
ffffffff81654730-ffffffff81654775: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168ed8d)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
Direct callers:
  - drivers/base/power/sysfs.c:runtime_suspended_time_show
  - drivers/base/power/sysfs.c:runtime_active_time_show
```
**Symbols:**

```
ffffffff81690010-ffffffff81690055: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void update_pm_runtime_accounting(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816af0bd)
Location: drivers/base/power/runtime.c:67
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
Direct callers:
  - drivers/base/power/sysfs.c:runtime_suspended_time_show
  - drivers/base/power/sysfs.c:runtime_active_time_show
```
**Symbols:**

```
ffffffff816b0670-ffffffff816b06b5: update_pm_runtime_accounting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9a5e)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff816e7ff0-ffffffff816e803b: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170dabe)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff8170c050-ffffffff8170c09b: update_pm_runtime_accounting.part.0 (STB_LOCAL)
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
In drivers/base/power/runtime.c (ffffffff817c97ee)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff817de2ee)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff817c2701)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff8184c2c1)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff81991c95)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff81b02105)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff81b501f5)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
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
In drivers/base/power/runtime.c (ffffffff81ba8775)
Location: drivers/base/power/runtime.c:66
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd0e8)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffff8000108fad60-ffff8000108fadcc: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (c09e8784)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
c09e64cc-c09e6558: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099995c)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
c000000000997960-c000000000997a04: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058bf48)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffe00058a366-ffffffe00058a3cc: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d320e)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff816d17a0-ffffffff816d17eb: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae4fe)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff816acac0-ffffffff816acb0b: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170177e)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff816ffd10-ffffffff816ffd5b: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c53e)
Location: drivers/base/power/runtime.c:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
**Symbols:**

```
ffffffff8171a7f0-ffffffff8171a83b: update_pm_runtime_accounting.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
