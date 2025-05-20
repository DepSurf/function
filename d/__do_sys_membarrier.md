# Function: <code>__do_sys_membarrier</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810e445c)
Location: kernel/sched/membarrier.c:283
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff810eebdc)
Location: kernel/sched/membarrier.c:283
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff810f59ec)
Location: kernel/sched/membarrier.c:274
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff8110172c)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff8110c072)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff81109217)
Location: kernel/sched/membarrier.c:579
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff8110af69)
Location: kernel/sched/membarrier.c:579
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff811297c9)
Location: kernel/sched/membarrier.c:580
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/build_utility.c (ffffffff81141a92)
Location: kernel/sched/membarrier.c:579
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
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
In kernel/sched/build_utility.c (ffffffff8116e4a2)
Location: kernel/sched/membarrier.c:579
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
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
In kernel/sched/build_utility.c (ffffffff8117eac2)
Location: kernel/sched/membarrier.c:614
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_membarrier(int cmd, unsigned int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/membarrier.c:620
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8118fa30-ffffffff8118fe54: __do_sys_membarrier (STB_LOCAL)
ffffffff821b18d0-ffffffff821b18f8: __do_sys_membarrier.cold (STB_LOCAL)
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
In kernel/sched/membarrier.c (0)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
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
In kernel/sched/membarrier.c (c03b2668)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
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
In kernel/sched/membarrier.c (c0000000001bd8dc)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffe0001085c6)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff810faa3c)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff810eac1c)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff810f7bfc)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
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
In kernel/sched/membarrier.c (ffffffff81102d3c)
Location: kernel/sched/membarrier.c:340
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
