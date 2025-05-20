# Function: <code>calc_load</code>

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
In kernel/sched/loadavg.c (ffffffff810b0ee3)
Location: kernel/sched/loadavg.c:100
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
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
In kernel/sched/loadavg.c (ffffffff810b3a39)
Location: kernel/sched/loadavg.c:100
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
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
In kernel/sched/loadavg.c (ffffffff810ba079)
Location: kernel/sched/loadavg.c:100
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
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
In kernel/sched/loadavg.c (ffffffff810b48ec)
Location: kernel/sched/loadavg.c:101
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
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
In kernel/sched/loadavg.c (ffffffff810bbbbc)
Location: kernel/sched/loadavg.c:102
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
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
In kernel/sched/loadavg.c (ffffffff810c328c)
Location: kernel/sched/loadavg.c:98
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
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
In kernel/sched/loadavg.c (ffffffff810cc53c)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff810ef24d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
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
In kernel/sched/loadavg.c (ffffffff810d4979)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff810f5ded)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810def39)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff81101b7d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810e7338)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff8110c40d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810e4f78)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff8110960d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810e6e56)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff8110b434)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810fe426)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff81129cec)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/build_utility.c (ffffffff811483fb)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_n
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
In kernel/sched/build_utility.c (ffffffff81176bcb)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_n
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
In kernel/sched/build_utility.c (ffffffff8118780b)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_n
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
In kernel/sched/build_utility.c (ffffffff81195fcb)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_n
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
In kernel/sched/loadavg.c (ffff80001013ea68)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffff800010166788)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (c038e998)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (c03b3bcc)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (c00000000018dbbc)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (c0000000001be1bc)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffe0000ed31e)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffe000108c86)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810d9129)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff810fae8d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810c7b29)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff810eb0ad)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810d5469)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff810f804d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
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
In kernel/sched/loadavg.c (ffffffff810e0d19)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_n
```
```
In kernel/sched/psi.c (ffffffff8110318d)
Location: include/linux/sched/loadavg.h:29
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
</details>
</li>
</ul>

## Differences
