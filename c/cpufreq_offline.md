# Function: <code>cpufreq_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817121d0)
Location: drivers/cpufreq/cpufreq.c:1361
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_callback
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff817121d0-ffffffff8171243e: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81744a40)
Location: drivers/cpufreq/cpufreq.c:1329
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81744a40-ffffffff81744ca8: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817630d0)
Location: drivers/cpufreq/cpufreq.c:1332
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff817630d0-ffffffff81763346: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9080)
Location: drivers/cpufreq/cpufreq.c:1364
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff817d9080-ffffffff817d92fc: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1362
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81821c90-ffffffff81821eba: cpufreq_offline (STB_LOCAL)
ffffffff81823229-ffffffff81823241: cpufreq_offline.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1367
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff8184db10-ffffffff8184dd3a: cpufreq_offline (STB_LOCAL)
ffffffff8184f0e9-ffffffff8184f101: cpufreq_offline.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1520
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81890ba0-ffffffff81890e0c: cpufreq_offline (STB_LOCAL)
ffffffff81892558-ffffffff81892570: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff818c2c80-ffffffff818c2eec: cpufreq_offline (STB_LOCAL)
ffffffff818c45eb-ffffffff818c4603: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1551
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81995070-ffffffff819952dd: cpufreq_offline.isra.0 (STB_LOCAL)
ffffffff8199683d-ffffffff81996855: cpufreq_offline.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1557
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81999740-ffffffff8199998f: cpufreq_offline.isra.0 (STB_LOCAL)
ffffffff81c2993d-ffffffff81c29955: cpufreq_offline.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1563
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff8197e270-ffffffff8197e4a6: cpufreq_offline.isra.0 (STB_LOCAL)
ffffffff81c1bcdb-ffffffff81c1bcf3: cpufreq_offline.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1572
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81a273d0-ffffffff81a275e8: cpufreq_offline.isra.0 (STB_LOCAL)
ffffffff81d2c142-ffffffff81d2c15a: cpufreq_offline.isra.0.cold (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81b909e5)
Location: drivers/cpufreq/cpufreq.c:1633
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
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
In drivers/cpufreq/cpufreq.c (ffffffff81d30c25)
Location: drivers/cpufreq/cpufreq.c:1630
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
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
In drivers/cpufreq/cpufreq.c (ffffffff81d99ea5)
Location: drivers/cpufreq/cpufreq.c:1637
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
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
In drivers/cpufreq/cpufreq.c (ffffffff81e51b55)
Location: drivers/cpufreq/cpufreq.c:1678
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1f610)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpufreq/cpufreq-dt.c (0)
Location: drivers/cpufreq/cpufreq-dt.c:303
Inline: False
```
**Symbols:**

```
ffff800010b1f610-ffff800010b1f908: cpufreq_offline (STB_LOCAL)
ffff800010b265e0-ffff800010b265fc: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9d90)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpufreq/cpufreq-dt.c (0)
Location: drivers/cpufreq/cpufreq-dt.c:303
Inline: False
```
**Symbols:**

```
c0bf9d90-c0bf9ffc: cpufreq_offline (STB_LOCAL)
c0c00428-c0c00444: cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c12760)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
c000000000c12760-c000000000c12b44: cpufreq_offline (STB_LOCAL)
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
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff818673a0-ffffffff8186760c: cpufreq_offline (STB_LOCAL)
ffffffff81868d0b-ffffffff81868d23: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81830050-ffffffff818302bc: cpufreq_offline (STB_LOCAL)
ffffffff818319bb-ffffffff818319d3: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff818b8130-ffffffff818b839c: cpufreq_offline (STB_LOCAL)
ffffffff818b9a9b-ffffffff818b9ab3: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cpufreq_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1534
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff818d43f0-ffffffff818d465c: cpufreq_offline (STB_LOCAL)
ffffffff818d5d7b-ffffffff818d5d93: cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
