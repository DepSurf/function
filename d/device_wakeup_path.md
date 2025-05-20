# Function: <code>device_wakeup_path</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0438)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_propagate_wakeup_to_parent
```
```
In drivers/base/power/domain.c (ffffffff817e59b8)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/main.c (ffffffff817c4f98)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
```
In drivers/base/power/domain.c (ffffffff817c9aa8)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/main.c (ffffffff8184f368)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
```
In drivers/base/power/domain.c (ffffffff81853fc8)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/main.c (ffffffff8199439a)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
```
In drivers/base/power/domain.c (ffffffff8199a568)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/main.c (ffffffff81b04dba)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
```
In drivers/base/power/domain.c (ffffffff81b0b6dd)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/main.c (ffffffff81b52675)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
```
In drivers/base/power/domain.c (ffffffff81b5971d)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/pmdomain/core.c (ffffffff81aa10dd)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_finish_resume
  - drivers/pmdomain/core.c:genpd_finish_suspend
```
```
In drivers/base/power/main.c (ffffffff81baad25)
Location: include/linux/pm_wakeup.h:87
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
