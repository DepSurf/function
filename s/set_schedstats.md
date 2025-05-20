# Function: <code>set_schedstats</code>

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
In kernel/sched/core.c (ffffffff81fa7323)
Location: kernel/sched/core.c:2286
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff81fe2fc2)
Location: kernel/sched/core.c:2296
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff820c3834)
Location: kernel/sched/core.c:2247
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff826cb861)
Location: kernel/sched/core.c:2266
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff826f59b0)
Location: kernel/sched/core.c:2242
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828ac7d2)
Location: kernel/sched/core.c:2236
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828c507f)
Location: kernel/sched/core.c:2645
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828cd6b9)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_schedstats(bool enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4448)
Location: kernel/sched/core.c:2924
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e6c32-ffffffff810e6c55: set_schedstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_schedstats(bool enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1e88)
Location: kernel/sched/core.c:3634
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81bdc448-ffffffff81bdc46b: set_schedstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_schedstats(bool enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3c98)
Location: kernel/sched/core.c:3655
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81bce5e1-ffffffff81bce604: set_schedstats (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810fa8f8)
Location: kernel/sched/core.c:4269
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
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
In kernel/sched/core.c (ffffffff8110c2a7)
Location: kernel/sched/core.c:4401
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
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
In kernel/sched/core.c (ffffffff811327a7)
Location: kernel/sched/core.c:4529
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
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
In kernel/sched/core.c (ffffffff81140d87)
Location: kernel/sched/core.c:4607
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
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
In kernel/sched/core.c (ffffffff8114be87)
Location: kernel/sched/core.c:4628
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:setup_schedstats
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
In kernel/sched/core.c (ffff800011444ed0)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (c151efac)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (c000000001369790)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffe000006db6)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828b6449)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828ae637)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828c93ab)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
In kernel/sched/core.c (ffffffff828ce69f)
Location: kernel/sched/core.c:2765
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
