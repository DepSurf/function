# Function: <code>update_cpumasks_hier</code>

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
In kernel/cpuset.c (ffffffff8111c9bb)
Location: kernel/cpuset.c:869
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cpuset.c (ffffffff811248ba)
Location: kernel/cpuset.c:880
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cpuset.c (ffffffff8112dcc8)
Location: kernel/cpuset.c:880
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8112f373)
Location: kernel/cgroup/cpuset.c:883
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8113c225)
Location: kernel/cgroup/cpuset.c:895
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8114aaaa)
Location: kernel/cgroup/cpuset.c:896
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811564f0)
Location: kernel/cgroup/cpuset.c:1259
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff811564f0-ffffffff811569ff: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:1220
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff81163460-ffffffff811639a6: update_cpumasks_hier (STB_LOCAL)
ffffffff8116564d-ffffffff81165660: update_cpumasks_hier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f290)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8116f290-ffffffff8116f7d8: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81180f90)
Location: kernel/cgroup/cpuset.c:1296
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff81180f90-ffffffff811814d4: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117de60)
Location: kernel/cgroup/cpuset.c:1319
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8117de60-ffffffff8117e3ca: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117de80)
Location: kernel/cgroup/cpuset.c:1319
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8117de80-ffffffff8117e3ea: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a5b00)
Location: kernel/cgroup/cpuset.c:1354
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff811a5b00-ffffffff811a606e: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d6f10)
Location: kernel/cgroup/cpuset.c:1392
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff811d6f10-ffffffff811d7477: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121baa0)
Location: kernel/cgroup/cpuset.c:1545
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8121baa0-ffffffff8121bff1: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:1553
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff81231d30-ffffffff812323e5: update_cpumasks_hier (STB_LOCAL)
ffffffff820dad14-ffffffff820dad72: update_cpumasks_hier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2181
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8124a3b0-ffffffff8124ab0d: update_cpumasks_hier (STB_LOCAL)
ffffffff821b69dc-ffffffff821b69f7: update_cpumasks_hier.cold (STB_LOCAL)
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
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e2b50)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffff8000101e2b50-ffff8000101e30ac: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c04237e8)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
c04237e8-c0423ce8: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0000000002525e0)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
c0000000002525e0-c000000000252c00: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe0001588da)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffe0001588da-ffffffe000158da4: update_cpumasks_hier (STB_LOCAL)
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
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811678b0)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff811678b0-ffffffff81167df8: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115aad0)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff8115aad0-ffffffff8115b012: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81165680)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff81165680-ffffffff81165bc8: update_cpumasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81172c00)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
```
**Symbols:**

```
ffffffff81172c00-ffffffff81173198: update_cpumasks_hier (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force</code>
</li>
</ul>
</details>
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
