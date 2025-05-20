# Function: <code>this_rq_lock_irq</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7e95)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff810ef828)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810ceea5)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff810f6cc2)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d8c65)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff81102a52)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810e1af5)
Location: kernel/sched/sched.h:1300
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff8110da71)
Location: kernel/sched/sched.h:1300
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810dee95)
Location: kernel/sched/sched.h:1358
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff8110ad91)
Location: kernel/sched/sched.h:1358
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810e0a85)
Location: kernel/sched/sched.h:1371
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff8110c9c1)
Location: kernel/sched/sched.h:1371
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810f6b85)
Location: kernel/sched/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff8112ba02)
Location: kernel/sched/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff811130d5)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/build_utility.c (ffffffff8114c197)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8113a1d5)
Location: kernel/sched/sched.h:1677
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/build_utility.c (ffffffff8117a8ff)
Location: kernel/sched/sched.h:1677
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff81149455)
Location: kernel/sched/sched.h:1704
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/build_utility.c (ffffffff8118b45f)
Location: kernel/sched/sched.h:1704
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff81154e55)
Location: kernel/sched/sched.h:1743
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/build_utility.c (ffffffff81199d90)
Location: kernel/sched/sched.h:1743
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffff800010138eac)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffff800010167850)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c0388208)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (c03b4678)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c0000000001853f8)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (c0000000001bf5f0)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffe0000e8bf2)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffe000109db4)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d3135)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff810fbd62)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810c1765)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff810ebf72)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d0815)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff810f8f22)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810da885)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
```
```
In kernel/sched/psi.c (ffffffff81104062)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
</ul>

## Differences
