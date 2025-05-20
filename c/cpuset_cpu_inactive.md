# Function: <code>cpuset_cpu_inactive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpuset_cpu_inactive(struct notifier_block *nfb, long unsigned int action, void *hcpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b00a0)
Location: kernel/sched/core.c:7266
Inline: True
```
**Symbols:**

```
ffffffff810b00a0-ffffffff810b01b5: cpuset_cpu_inactive (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b29e1)
Location: kernel/sched/core.c:7190
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810b8fd1)
Location: kernel/sched/core.c:7311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810b3b87)
Location: kernel/sched/core.c:5554
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810bae27)
Location: kernel/sched/core.c:5633
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810c2311)
Location: kernel/sched/core.c:5759
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810cb610)
Location: kernel/sched/core.c:5735
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810d361f)
Location: kernel/sched/core.c:6187
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810ddb8f)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810e634f)
Location: kernel/sched/core.c:6611
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810e41a6)
Location: kernel/sched/core.c:7445
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810e617e)
Location: kernel/sched/core.c:7814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810fd473)
Location: kernel/sched/core.c:9011
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff81119e57)
Location: kernel/sched/core.c:9299
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff81141714)
Location: kernel/sched/core.c:9489
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff8114d3c2)
Location: kernel/sched/core.c:9634
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff81159082)
Location: kernel/sched/core.c:9623
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffff80001013d430)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (c038d4a0)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (c00000000018c200)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffe0000ec7de)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810d7d7f)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810c669f)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810d456f)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810df97f)
Location: kernel/sched/core.c:6376
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
