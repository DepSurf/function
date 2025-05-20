# Function: <code>cpudl_heapify_down</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ce167)
Location: kernel/sched/cpudeadline.c:34
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810caab7)
Location: kernel/sched/cpudeadline.c:34
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810d2267)
Location: kernel/sched/cpudeadline.c:34
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810da338)
Location: kernel/sched/cpudeadline.c:30
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810e3e88)
Location: kernel/sched/cpudeadline.c:30
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810eaa78)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810f6448)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpudl_heapify_down(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ffcc0)
Location: kernel/sched/cpudeadline.c:26
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ffcc0-ffffffff810ffda2: cpudl_heapify_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpudl_heapify_down(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810fe790)
Location: kernel/sched/cpudeadline.c:26
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810fe790-ffffffff810fe872: cpudl_heapify_down (STB_LOCAL)
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
In kernel/sched/cpudeadline.c (ffffffff81100c5a)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff8111cdca)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/build_policy.c (ffffffff8112ddfa)
Location: kernel/sched/cpudeadline.c:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_heapify
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
In kernel/sched/build_policy.c (ffffffff81157c7a)
Location: kernel/sched/cpudeadline.c:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_heapify
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
In kernel/sched/build_policy.c (ffffffff81167d39)
Location: kernel/sched/cpudeadline.c:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_heapify
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
In kernel/sched/build_policy.c (ffffffff81174b39)
Location: kernel/sched/cpudeadline.c:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffff80001015a2a0)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (c03a7020)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (c0000000001ae528)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffe0000ffc42)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810ef848)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810df8b8)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810ec978)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
In kernel/sched/cpudeadline.c (ffffffff810f79b8)
Location: kernel/sched/cpudeadline.c:26
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_heapify
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
