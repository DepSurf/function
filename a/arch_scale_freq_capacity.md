# Function: <code>arch_scale_freq_capacity</code>

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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1401
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1401
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1401
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1438
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1438
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1438
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1477
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1477
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1477
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1658
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1658
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1658
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1697
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1697
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1697
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1731
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1731
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1731
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
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1877
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: kernel/sched/sched.h:1877
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1939
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1939
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (ffffffff810dffb5)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/deadline.c (ffffffff810fcc3d)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810dd415)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/deadline.c (ffffffff810fb152)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810dee85)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/deadline.c (ffffffff810fd35d)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810f3dc3)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/deadline.c (ffffffff8111972b)
Location: arch/x86/include/asm/topology.h:205
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff81110267)
Location: arch/x86/include/asm/topology.h:209
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/build_policy.c (ffffffff811361bc)
Location: arch/x86/include/asm/topology.h:209
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff81137177)
Location: arch/x86/include/asm/topology.h:209
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/build_policy.c (ffffffff8116079c)
Location: arch/x86/include/asm/topology.h:209
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff811461e7)
Location: arch/x86/include/asm/topology.h:217
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/build_policy.c (ffffffff81170ec4)
Location: arch/x86/include/asm/topology.h:217
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff811517b7)
Location: arch/x86/include/asm/topology.h:217
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/build_policy.c (ffffffff8117e5f3)
Location: arch/x86/include/asm/topology.h:217
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl_se
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1982
Inline: True
```
</details>
</li>
</ul>

## Differences
