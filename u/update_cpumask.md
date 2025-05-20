# Function: <code>update_cpumask</code>

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
In kernel/cpuset.c (ffffffff8111c7e0)
Location: kernel/cpuset.c:931
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
In kernel/cpuset.c (ffffffff811246e0)
Location: kernel/cpuset.c:942
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
In kernel/cpuset.c (ffffffff8112db59)
Location: kernel/cpuset.c:942
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
In kernel/cgroup/cpuset.c (ffffffff8112f1cf)
Location: kernel/cgroup/cpuset.c:945
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
In kernel/cgroup/cpuset.c (ffffffff8113c07b)
Location: kernel/cgroup/cpuset.c:956
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
In kernel/cgroup/cpuset.c (ffffffff8114a9e6)
Location: kernel/cgroup/cpuset.c:957
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff81157502)
Location: kernel/cgroup/cpuset.c:1441
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8116409b)
Location: kernel/cgroup/cpuset.c:1402
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8116fedc)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811819a0)
Location: kernel/cgroup/cpuset.c:1478
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811819a0-ffffffff81181bdc: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117e8b0)
Location: kernel/cgroup/cpuset.c:1501
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8117e8b0-ffffffff8117eaec: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117e8c0)
Location: kernel/cgroup/cpuset.c:1501
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8117e8c0-ffffffff8117eafc: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a65e0)
Location: kernel/cgroup/cpuset.c:1548
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811a65e0-ffffffff811a681c: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d7a60)
Location: kernel/cgroup/cpuset.c:1586
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811d7a60-ffffffff811d7cbd: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121c780)
Location: kernel/cgroup/cpuset.c:1736
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8121c780-ffffffff8121cbb7: update_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:1763
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff81232b70-ffffffff8123300d: update_cpumask (STB_LOCAL)
ffffffff820dad72-ffffffff820dad95: update_cpumask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2422
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8124c2f0-ffffffff8124c93a: update_cpumask (STB_LOCAL)
ffffffff821b69f7-ffffffff821b6a45: update_cpumask.cold (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffff8000101e3978)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (c0424660)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_cpumask(struct cpuset *cs, struct cpuset *trialcs, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000252ce0)
Location: kernel/cgroup/cpuset.c:1476
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
c000000000252ce0-c000000000252fa4: update_cpumask (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffffffe000159f3c)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff811684fc)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8115b710)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff811662cc)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff811738f7)
Location: kernel/cgroup/cpuset.c:1476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
<b>Arch</b>
<ul>
</ul>
