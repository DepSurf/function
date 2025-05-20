# Function: <code>to_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81559ef8)
Location: drivers/base/power/power.h:115
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/trace.c (0)
Location: drivers/base/power/power.h:115
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad45d)
Location: drivers/base/power/power.h:117
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff815aef34)
Location: drivers/base/power/power.h:117
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff815dc21d)
Location: drivers/base/power/power.h:134
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff815ddd47)
Location: drivers/base/power/power.h:134
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff815f0d96)
Location: drivers/base/power/power.h:134
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff815f29c6)
Location: drivers/base/power/power.h:134
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff816582e6)
Location: drivers/base/power/power.h:135
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff81659f76)
Location: drivers/base/power/power.h:135
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81693cf8)
Location: drivers/base/power/power.h:101
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff81695c25)
Location: drivers/base/power/power.h:101
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff816b4378)
Location: drivers/base/power/power.h:101
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff816b6275)
Location: drivers/base/power/power.h:101
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff816ee243)
Location: drivers/base/power/power.h:102
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff816f00cf)
Location: drivers/base/power/power.h:102
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81712223)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff81714575)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff817cdbd3)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff82d1f109)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff817e252d)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff8300cfb4)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff817c690d)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff83217e0a)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81850cc9)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff83301836)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81996739)
Location: drivers/base/power/power.h:108
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff834ba6dd)
Location: drivers/base/power/power.h:108
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81b07440)
Location: drivers/base/power/power.h:108
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff83ef7f0d)
Location: drivers/base/power/power.h:108
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81b55490)
Location: drivers/base/power/power.h:109
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff8371daad)
Location: drivers/base/power/power.h:109
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81bada50)
Location: drivers/base/power/power.h:109
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/base/power/trace.c (ffffffff8395161d)
Location: drivers/base/power/power.h:109
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffff800010902c34)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (c09ed04c)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (c0000000009a11b4)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/base/power/main.c (ffffffff816d85a3)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff816da8a5)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff816b2c03)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff816b4f25)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff81705ee3)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff81708235)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
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
In drivers/base/power/main.c (ffffffff817208ae)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/base/power/trace.c (ffffffff81722c65)
Location: drivers/base/power/power.h:105
Inline: True
Inline callers:
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
</details>
</li>
</ul>

## Differences
