# Function: <code>find_process_by_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa128)
Location: kernel/sched/core.c:3602
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0cde)
Location: kernel/sched/core.c:3855
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810b6f3e)
Location: kernel/sched/core.c:3892
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810b325e)
Location: kernel/sched/core.c:3898
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810b53a0)
Location: kernel/sched/core.c:3942
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810bcd90)
Location: kernel/sched/core.c:4069
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810c5fb0)
Location: kernel/sched/core.c:4054
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810cbbb0)
Location: kernel/sched/core.c:4473
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810d5710)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810dfce0)
Location: kernel/sched/core.c:4908
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810dcfd0)
Location: kernel/sched/core.c:5681
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810deba0)
Location: kernel/sched/core.c:6010
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810f3ad0)
Location: kernel/sched/core.c:7173
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff8110fb67)
Location: kernel/sched/core.c:7265
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff81136a17)
Location: kernel/sched/core.c:7407
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff81145a57)
Location: kernel/sched/core.c:7508
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff8115817a)
Location: kernel/sched/core.c:7557
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffff800010136258)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_getscheduler
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (c03851a4)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
c0382a14-c0382a3c: find_process_by_pid.part.0 (STB_LOCAL)
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
In kernel/sched/core.c (c000000000181374)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffe0000ec230)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810cfa10)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810be2d0)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810ce5a0)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
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
In kernel/sched/core.c (ffffffff810d7581)
Location: kernel/sched/core.c:4675
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
```
</details>
</li>
</ul>

## Differences
