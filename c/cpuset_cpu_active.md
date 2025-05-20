# Function: <code>cpuset_cpu_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpuset_cpu_active(struct notifier_block *nfb, long unsigned int action, void *hcpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0050)
Location: kernel/sched/core.c:7232
Inline: True
```
**Symbols:**

```
ffffffff810b0050-ffffffff810b009e: cpuset_cpu_active (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b295e)
Location: kernel/sched/core.c:7167
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810b8f51)
Location: kernel/sched/core.c:7288
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810b3ad5)
Location: kernel/sched/core.c:5532
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810bad75)
Location: kernel/sched/core.c:5611
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810c225b)
Location: kernel/sched/core.c:5737
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810cb577)
Location: kernel/sched/core.c:5713
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810d358a)
Location: kernel/sched/core.c:6165
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810ddaf5)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810e62b2)
Location: kernel/sched/core.c:6589
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810e4041)
Location: kernel/sched/core.c:7423
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810e6011)
Location: kernel/sched/core.c:7792
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810fd1d8)
Location: kernel/sched/core.c:8989
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff81119bb5)
Location: kernel/sched/core.c:9277
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff81141507)
Location: kernel/sched/core.c:9467
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff8114d19c)
Location: kernel/sched/core.c:9612
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff81158e5c)
Location: kernel/sched/core.c:9601
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffff80001013d268)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (c038d414)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (c00000000018c0ac)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffe0000ec732)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810d7ce5)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810c6605)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810d44d5)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/sched/core.c (ffffffff810df8e5)
Location: kernel/sched/core.c:6354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
