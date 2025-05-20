# Function: <code>cpuidle_get_device</code>

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
In kernel/sched/idle.c (ffffffff810c7ca0)
Location: include/linux/cpuidle.h:155
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In kernel/sched/idle.c (ffffffff810cd990)
Location: include/linux/cpuidle.h:157
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174fc1c)
Location: include/linux/cpuidle.h:157
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810ca3a6)
Location: include/linux/cpuidle.h:157
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e6c9)
Location: include/linux/cpuidle.h:157
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810d1bbe)
Location: include/linux/cpuidle.h:158
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e3f99)
Location: include/linux/cpuidle.h:158
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810c42d7)
Location: include/linux/cpuidle.h:163
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d1a9)
Location: include/linux/cpuidle.h:163
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810cd597)
Location: include/linux/cpuidle.h:156
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81859189)
Location: include/linux/cpuidle.h:156
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810d5982)
Location: include/linux/cpuidle.h:155
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cac9)
Location: include/linux/cpuidle.h:155
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810dff92)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cede9)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810e8224)
Location: include/linux/cpuidle.h:167
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a1669)
Location: include/linux/cpuidle.h:167
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810e5e44)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a46d9)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810e7e04)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81989229)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810ff4b4)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33509)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/build_policy.c (ffffffff81133514)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81b9fdbc)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/build_policy.c (ffffffff8115d8d4)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d418bc)
Location: include/linux/cpuidle.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/build_policy.c (ffffffff8116e014)
Location: include/linux/cpuidle.h:203
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81dac28c)
Location: include/linux/cpuidle.h:203
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/build_policy.c (ffffffff8117b5d4)
Location: include/linux/cpuidle.h:203
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81e6432c)
Location: include/linux/cpuidle.h:203
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffff80001013fcc8)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26b00)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (c038fc08)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (c0c01904)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (c00000000018ed7c)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1db70)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (0)
Location: include/linux/cpuidle.h:202
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
In kernel/sched/idle.c (ffffffff810da182)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818729e9)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810c916c)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c689)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810d64c2)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4299)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
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
In kernel/sched/idle.c (ffffffff810e1dc2)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e060c)
Location: include/linux/cpuidle.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
</details>
</li>
</ul>

## Differences
