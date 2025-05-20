# Function: <code>update_sibling_cpumasks</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81156a00)
Location: kernel/cgroup/cpuset.c:1412
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff81156a00-ffffffff81156a7f: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811639b0)
Location: kernel/cgroup/cpuset.c:1373
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff811639b0-ffffffff81163a2e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f7e0)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff8116f7e0-ffffffff8116f85e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811814e0)
Location: kernel/cgroup/cpuset.c:1449
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff811814e0-ffffffff8118155e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117e3d0)
Location: kernel/cgroup/cpuset.c:1472
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff8117e3d0-ffffffff8117e453: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117e3f0)
Location: kernel/cgroup/cpuset.c:1472
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff8117e3f0-ffffffff8117e473: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a6070)
Location: kernel/cgroup/cpuset.c:1509
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff811a6070-ffffffff811a618b: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d7480)
Location: kernel/cgroup/cpuset.c:1547
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff811d7480-ffffffff811d75ad: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121c010)
Location: kernel/cgroup/cpuset.c:1697
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff8121c010-ffffffff8121c13f: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81232400)
Location: kernel/cgroup/cpuset.c:1724
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
ffffffff81232400-ffffffff8123252b: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8124ab20)
Location: kernel/cgroup/cpuset.c:2371
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_partition_disable
```
**Symbols:**

```
ffffffff8124ab20-ffffffff8124acbf: update_sibling_cpumasks (STB_LOCAL)
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
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e30b0)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffff8000101e30b0-ffff8000101e3144: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0423ce8)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
c0423ce8-c0423d78: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000252c00)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
```
**Symbols:**

```
c000000000252c00-c000000000252cd8: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000158da4)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffe000158da4-ffffffe000158e1c: update_sibling_cpumasks (STB_LOCAL)
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
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81167e00)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff81167e00-ffffffff81167e7e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115b020)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff8115b020-ffffffff8115b09e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81165bd0)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff81165bd0-ffffffff81165c4e: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset *parent, struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811731a0)
Location: kernel/cgroup/cpuset.c:1447
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
```
**Symbols:**

```
ffffffff811731a0-ffffffff81173228: update_sibling_cpumasks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
