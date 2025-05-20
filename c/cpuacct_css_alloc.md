# Function: <code>cpuacct_css_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810c9910)
Location: kernel/sched/cpuacct.c:60
Inline: False
```
**Symbols:**

```
ffffffff810c9910-ffffffff810c99a7: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ce0c0)
Location: kernel/sched/cpuacct.c:69
Inline: False
```
**Symbols:**

```
ffffffff810ce0c0-ffffffff810ce157: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d40d0)
Location: kernel/sched/cpuacct.c:69
Inline: False
```
**Symbols:**

```
ffffffff810d40d0-ffffffff810d4167: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d3270)
Location: kernel/sched/cpuacct.c:69
Inline: True
```
**Symbols:**

```
ffffffff810d3270-ffffffff810d3307: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810dae40)
Location: kernel/sched/cpuacct.c:70
Inline: True
```
**Symbols:**

```
ffffffff810dae40-ffffffff810daed7: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e3090)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810e3090-ffffffff810e3129: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ed7c0)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810ed7c0-ffffffff810ed859: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f4550)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810f4550-ffffffff810f45f5: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811001e0)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff811001e0-ffffffff81100285: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff8110a690)
Location: kernel/sched/cpuacct.c:60
Inline: True
```
**Symbols:**

```
ffffffff8110a690-ffffffff8110a726: cpuacct_css_alloc.part.0 (STB_LOCAL)
ffffffff8110a730-ffffffff8110a74d: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811075a0)
Location: kernel/sched/cpuacct.c:60
Inline: True
```
**Symbols:**

```
ffffffff811075a0-ffffffff81107636: cpuacct_css_alloc.part.0 (STB_LOCAL)
ffffffff81107640-ffffffff8110765d: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81109670)
Location: kernel/sched/cpuacct.c:60
Inline: True
```
**Symbols:**

```
ffffffff81109670-ffffffff81109713: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811279a0)
Location: kernel/sched/cpuacct.c:56
Inline: True
```
**Symbols:**

```
ffffffff811279a0-ffffffff81127a43: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811422b0)
Location: kernel/sched/cpuacct.c:55
Inline: True
```
**Symbols:**

```
ffffffff811422b0-ffffffff81142355: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116e090)
Location: kernel/sched/cpuacct.c:55
Inline: True
```
**Symbols:**

```
ffffffff8116e090-ffffffff8116e135: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e590)
Location: kernel/sched/cpuacct.c:55
Inline: True
```
**Symbols:**

```
ffffffff8117e590-ffffffff8117e635: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c330)
Location: kernel/sched/cpuacct.c:55
Inline: True
```
**Symbols:**

```
ffffffff8118c330-ffffffff8118c408: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffff800010164828)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffff800010164828-ffff8000101648d8: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c03b0d84)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
c03b0d84-c03b0e24: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c0000000001bb740)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
c0000000001bb740-c0000000001bb834: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffe0001080bc)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffe0001080bc-ffffffe00010814e: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f94f0)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810f94f0-ffffffff810f9595: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e96d0)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810e96d0-ffffffff810e9775: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f6710)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff810f6710-ffffffff810f67b5: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuacct_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81101730)
Location: kernel/sched/cpuacct.c:59
Inline: True
```
**Symbols:**

```
ffffffff81101730-ffffffff811017d5: cpuacct_css_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
