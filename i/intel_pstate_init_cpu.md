# Function: <code>intel_pstate_init_cpu</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff816ba7ac)
Location: drivers/cpufreq/intel_pstate.c:1045
Inline: True
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
In drivers/cpufreq/intel_pstate.c (ffffffff8171c6fd)
Location: drivers/cpufreq/intel_pstate.c:1382
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174e730)
Location: drivers/cpufreq/intel_pstate.c:1872
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8174e730-ffffffff8174ea03: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176ce90)
Location: drivers/cpufreq/intel_pstate.c:1883
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff8176ce90-ffffffff8176d154: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2e40)
Location: drivers/cpufreq/intel_pstate.c:1648
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff817e2e40-ffffffff817e3065: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1825
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff8182b920-ffffffff8182bb39: intel_pstate_init_cpu (STB_LOCAL)
ffffffff8182cd32-ffffffff8182cd5f: intel_pstate_init_cpu.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1888
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff818578a0-ffffffff81857ab9: intel_pstate_init_cpu (STB_LOCAL)
ffffffff81858d12-ffffffff81858d3f: intel_pstate_init_cpu.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1913
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff8189b400-ffffffff8189b637: intel_pstate_init_cpu (STB_LOCAL)
ffffffff8189c613-ffffffff8189c640: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff818cd5b0-ffffffff818cd7e7: intel_pstate_init_cpu (STB_LOCAL)
ffffffff818ce8e8-ffffffff818ce915: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1967
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff8199efd0-ffffffff8199f125: intel_pstate_init_cpu (STB_LOCAL)
ffffffff819a0db1-ffffffff819a0dde: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a2c60)
Location: drivers/cpufreq/intel_pstate.c:2115
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff819a2c60-ffffffff819a2d7d: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81986380)
Location: drivers/cpufreq/intel_pstate.c:2112
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81986380-ffffffff819865bf: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30720)
Location: drivers/cpufreq/intel_pstate.c:2273
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81a30720-ffffffff81a3083a: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ca60)
Location: drivers/cpufreq/intel_pstate.c:2443
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81b9ca60-ffffffff81b9cb7f: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3e580)
Location: drivers/cpufreq/intel_pstate.c:2407
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81d3e580-ffffffff81d3e69f: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da9110)
Location: drivers/cpufreq/intel_pstate.c:2431
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81da9110-ffffffff81da921a: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e61090)
Location: drivers/cpufreq/intel_pstate.c:2456
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81e61090-ffffffff81e611c9: intel_pstate_init_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff818711b0-ffffffff818713e7: intel_pstate_init_cpu (STB_LOCAL)
ffffffff818724e8-ffffffff81872515: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff8183a340-ffffffff8183a577: intel_pstate_init_cpu (STB_LOCAL)
ffffffff8183c18e-ffffffff8183c1bb: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff818c2a60-ffffffff818c2c97: intel_pstate_init_cpu (STB_LOCAL)
ffffffff818c3d98-ffffffff818c3dc5: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init
```
**Symbols:**

```
ffffffff818dedc0-ffffffff818deff7: intel_pstate_init_cpu (STB_LOCAL)
ffffffff818e0108-ffffffff818e0135: intel_pstate_init_cpu.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
