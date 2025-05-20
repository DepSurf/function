# Function: <code>sd_alloc_ctl_cpu_table</code>

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
In kernel/sched/core.c (ffffffff810a5eb1)
Location: kernel/sched/core.c:5416
Inline: True
Inline callers:
  - kernel/sched/core.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810cb3bb)
Location: kernel/sched/debug.c:304
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810d13ec)
Location: kernel/sched/debug.c:304
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810d050d)
Location: kernel/sched/debug.c:305
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810d7e91)
Location: kernel/sched/debug.c:310
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810df34b)
Location: kernel/sched/debug.c:285
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810e9acb)
Location: kernel/sched/debug.c:286
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810f0a56)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810fc706)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ctl_table *sd_alloc_ctl_cpu_table(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81106f30)
Location: kernel/sched/debug.c:269
Inline: False
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
**Symbols:**

```
ffffffff81106f30-ffffffff8110705d: sd_alloc_ctl_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_table *sd_alloc_ctl_cpu_table(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81105590)
Location: kernel/sched/debug.c:323
Inline: False
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
**Symbols:**

```
ffffffff81105590-ffffffff811056bd: sd_alloc_ctl_cpu_table (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161b0c)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (c03ae2f8)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (c0000000001b7cf8)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffe0001058b6)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810f5a36)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810e5bf6)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810f2c36)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
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
In kernel/sched/debug.c (ffffffff810fdc36)
Location: kernel/sched/debug.c:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
