# Function: <code>update_top_cache_domain</code>

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
In kernel/sched/core.c (ffffffff810a8492)
Location: kernel/sched/core.c:5995
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
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
In kernel/sched/core.c (ffffffff810ab03a)
Location: kernel/sched/core.c:5956
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
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
In kernel/sched/core.c (ffffffff810b12b8)
Location: kernel/sched/core.c:6000
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810cb59f)
Location: kernel/sched/topology.c:395
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810d2d59)
Location: kernel/sched/topology.c:410
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810dad20)
Location: kernel/sched/topology.c:402
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810e4870)
Location: kernel/sched/topology.c:598
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810eb829)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810f71d8)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100980)
Location: kernel/sched/topology.c:625
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81100980-ffffffff81100b1f: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ff4d0)
Location: kernel/sched/topology.c:653
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810ff4d0-ffffffff810ff66f: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101cc0)
Location: kernel/sched/topology.c:653
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81101cc0-ffffffff81101e68: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111dee0)
Location: kernel/sched/topology.c:653
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8111dee0-ffffffff8111e220: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81142720)
Location: kernel/sched/topology.c:673
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81142720-ffffffff81142a60: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116e9a0)
Location: kernel/sched/topology.c:673
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8116e9a0-ffffffff8116ece0: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117f1f0)
Location: kernel/sched/topology.c:675
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8117f1f0-ffffffff8117f519: update_top_cache_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_top_cache_domain(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118d8b0)
Location: kernel/sched/topology.c:680
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8118d8b0-ffffffff8118dc55: update_top_cache_domain (STB_LOCAL)
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
In kernel/sched/topology.c (ffff80001015b580)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (c03a7f58)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (c0000000001afb60)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffe000100820)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810f05d8)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810e0648)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810ed708)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff810f8748)
Location: kernel/sched/topology.c:627
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
