# Function: <code>rebuild_sched_domains_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111ad10)
Location: kernel/cpuset.c:800
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8111ad10-ffffffff8111ad84: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81122be0)
Location: kernel/cpuset.c:811
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff81122be0-ffffffff81122c54: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112cca0)
Location: kernel/cpuset.c:811
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8112cca0-ffffffff8112cd15: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112dee0)
Location: kernel/cgroup/cpuset.c:814
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8112dee0-ffffffff8112df55: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113aa70)
Location: kernel/cgroup/cpuset.c:826
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8113aa70-ffffffff8113aae5: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:827
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff81149a60-ffffffff81149f3a: rebuild_sched_domains_locked (STB_LOCAL)
ffffffff8114c26b-ffffffff8114c291: rebuild_sched_domains_locked.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:947
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff81155750-ffffffff81155cfb: rebuild_sched_domains_locked (STB_LOCAL)
ffffffff81158e9b-ffffffff81158ec2: rebuild_sched_domains_locked.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81163000)
Location: kernel/cgroup/cpuset.c:908
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff81163000-ffffffff811630a8: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116ed00)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8116ed00-ffffffff8116eed0: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117ff60)
Location: kernel/cgroup/cpuset.c:984
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff8117ff60-ffffffff81180041: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117d060)
Location: kernel/cgroup/cpuset.c:984
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff8117d060-ffffffff8117d1be: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117c1e0)
Location: kernel/cgroup/cpuset.c:984
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff8117c1e0-ffffffff8117c442: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a3d70)
Location: kernel/cgroup/cpuset.c:1012
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff811a3d70-ffffffff811a3fd2: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d5650)
Location: kernel/cgroup/cpuset.c:1052
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff811d5650-ffffffff811d58d9: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81219cc0)
Location: kernel/cgroup/cpuset.c:1139
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff81219cc0-ffffffff81219f49: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122fb60)
Location: kernel/cgroup/cpuset.c:1142
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
**Symbols:**

```
ffffffff8122fb60-ffffffff8122fde9: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81248530)
Location: kernel/cgroup/cpuset.c:1206
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_partition_sd_lb
  - kernel/cgroup/cpuset.c:update_partition_sd_lb
```
**Symbols:**

```
ffffffff81248530-ffffffff812487d2: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e16d0)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffff8000101e16d0-ffff8000101e1924: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c04229b4)
Location: kernel/cgroup/cpuset.c:982
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
c04229b4-c0422c00: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000251b80)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
c000000000251b80-c000000000251e5c: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157b48)
Location: kernel/cgroup/cpuset.c:982
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffe000157b48-ffffffe000157cea: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81167320)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff81167320-ffffffff811674f0: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115a550)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff8115a550-ffffffff8115a720: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811650f0)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff811650f0-ffffffff811652c0: rebuild_sched_domains_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rebuild_sched_domains_locked();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811725a0)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
**Symbols:**

```
ffffffff811725a0-ffffffff811727d0: rebuild_sched_domains_locked (STB_LOCAL)
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
