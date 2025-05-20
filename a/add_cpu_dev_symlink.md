# Function: <code>add_cpu_dev_symlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_cpu_dev_symlink(struct cpufreq_policy *policy, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816afbf0)
Location: drivers/cpufreq/cpufreq.c:876
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff816afbf0-ffffffff816afc77: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_cpu_dev_symlink(struct cpufreq_policy *policy, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817111e0)
Location: drivers/cpufreq/cpufreq.c:919
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817111e0-ffffffff81711263: add_cpu_dev_symlink (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81745fc4)
Location: drivers/cpufreq/cpufreq.c:921
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761750)
Location: drivers/cpufreq/cpufreq.c:931
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81761750-ffffffff817617db: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d7700)
Location: drivers/cpufreq/cpufreq.c:963
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817d7700-ffffffff817d778b: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820110)
Location: drivers/cpufreq/cpufreq.c:957
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81820110-ffffffff8182019b: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184bfc0)
Location: drivers/cpufreq/cpufreq.c:962
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8184bfc0-ffffffff8184c04b: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:986
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8188f0f0-ffffffff8188f168: add_cpu_dev_symlink (STB_LOCAL)
ffffffff818923be-ffffffff818923d2: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818c10d0-ffffffff818c1148: add_cpu_dev_symlink (STB_LOCAL)
ffffffff818c4492-ffffffff818c44a6: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1003
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81992e50-ffffffff81992ec8: add_cpu_dev_symlink (STB_LOCAL)
ffffffff8199664d-ffffffff81996661: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1009
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81996070-ffffffff819960e8: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81c296b7-ffffffff81c296cb: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1006
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8197ae40-ffffffff8197aeb8: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81c1ba5e-ffffffff81c1ba72: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a24244)
Location: drivers/cpufreq/cpufreq.c:1007
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81a24220-ffffffff81a24289: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81d2bdb8-ffffffff81d2bdcc: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8d944)
Location: drivers/cpufreq/cpufreq.c:1011
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81b8d920-ffffffff81b8d9a5: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81ef8008-ffffffff81ef801c: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d280)
Location: drivers/cpufreq/cpufreq.c:1002
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d2d280-ffffffff81d2d327: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d964f0)
Location: drivers/cpufreq/cpufreq.c:1009
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d964f0-ffffffff81d96597: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e150)
Location: drivers/cpufreq/cpufreq.c:1044
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81e4e150-ffffffff81e4e1f7: add_cpu_dev_symlink (STB_LOCAL)
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
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1f508)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff800010b1f508-ffff800010b1f60c: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf8a90)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0bf8a90-c0bf8b34: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c10e70)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c000000000c10e70-c000000000c10f70: add_cpu_dev_symlink (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818657f0-ffffffff81865868: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81868bb2-ffffffff81868bc6: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8182e4a0-ffffffff8182e518: add_cpu_dev_symlink (STB_LOCAL)
ffffffff81831862-ffffffff81831876: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818b6580-ffffffff818b65f8: add_cpu_dev_symlink (STB_LOCAL)
ffffffff818b9942-ffffffff818b9956: add_cpu_dev_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void add_cpu_dev_symlink(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:992
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818d2830-ffffffff818d28a8: add_cpu_dev_symlink (STB_LOCAL)
ffffffff818d5c22-ffffffff818d5c36: add_cpu_dev_symlink.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
