# Function: <code>sd_alloc_ctl_domain_table</code>

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
In kernel/sched/core.c (ffffffff810a5fcb)
Location: kernel/sched/core.c:5376
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
In kernel/sched/debug.c (ffffffff810cb4b2)
Location: kernel/sched/debug.c:264
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
In kernel/sched/debug.c (ffffffff810d14e5)
Location: kernel/sched/debug.c:264
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
In kernel/sched/debug.c (ffffffff810d05f0)
Location: kernel/sched/debug.c:265
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
In kernel/sched/debug.c (ffffffff810d7f53)
Location: kernel/sched/debug.c:270
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
In kernel/sched/debug.c (ffffffff810df41f)
Location: kernel/sched/debug.c:260
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
In kernel/sched/debug.c (ffffffff810e9b9f)
Location: kernel/sched/debug.c:261
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
In kernel/sched/debug.c (ffffffff810f0afa)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffff810fc7aa)
Location: kernel/sched/debug.c:249
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
struct ctl_table *sd_alloc_ctl_domain_table(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81106d50)
Location: kernel/sched/debug.c:249
Inline: False
Direct callers:
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
```
**Symbols:**

```
ffffffff81106d50-ffffffff81106f26: sd_alloc_ctl_domain_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_table *sd_alloc_ctl_domain_table(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff811053b0)
Location: kernel/sched/debug.c:303
Inline: False
Direct callers:
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
```
**Symbols:**

```
ffffffff811053b0-ffffffff81105586: sd_alloc_ctl_domain_table (STB_LOCAL)
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
In kernel/sched/debug.c (ffff800010161bd0)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (c03ae3e0)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (c0000000001b7de8)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffe0001058c0)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffff810f5ada)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffff810e5c9a)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffff810f2cda)
Location: kernel/sched/debug.c:249
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
In kernel/sched/debug.c (ffffffff810fdcda)
Location: kernel/sched/debug.c:249
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
