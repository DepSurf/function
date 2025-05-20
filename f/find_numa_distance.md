# Function: <code>find_numa_distance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aedd0)
Location: kernel/sched/core.c:6577
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810aedd0-ffffffff810aee27: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b15e0)
Location: kernel/sched/core.c:6543
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810b15e0-ffffffff810b1637: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b78b0)
Location: kernel/sched/core.c:6640
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff810b78b0-ffffffff810b7907: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cbb00)
Location: kernel/sched/topology.c:1260
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810cbb00-ffffffff810cbb5f: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4330)
Location: kernel/sched/topology.c:1263
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810d4330-ffffffff810d438f: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dbf40)
Location: kernel/sched/topology.c:1258
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810dbf40-ffffffff810dbf9f: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e5b70)
Location: kernel/sched/topology.c:1462
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810e5b70-ffffffff810e5bcf: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ec7c0)
Location: kernel/sched/topology.c:1487
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810ec7c0-ffffffff810ec817: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8260)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810f8260-ffffffff810f82b7: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811023c4)
Location: kernel/sched/topology.c:1473
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81102270-ffffffff811022cd: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100fd4)
Location: kernel/sched/topology.c:1532
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81100e80-ffffffff81100edd: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103240)
Location: kernel/sched/topology.c:1563
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81103240-ffffffff8110329d: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120040)
Location: kernel/sched/topology.c:1694
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81120040-ffffffff8112009d: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114a1b0)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff8114a1b0-ffffffff8114a222: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81178b60)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81178b60-ffffffff81178bd2: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81189750)
Location: kernel/sched/topology.c:1725
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81189750-ffffffff811897c2: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198050)
Location: kernel/sched/topology.c:1751
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
```
**Symbols:**

```
ffffffff81198050-ffffffff811980c2: find_numa_distance (STB_GLOBAL)
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
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015c830)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffff80001015c830-ffff80001015c8b4: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b10a0)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
c0000000001b10a0-c0000000001b1158: find_numa_distance (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1660)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810f1660-ffffffff810f16b7: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e16d0)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810e16d0-ffffffff810e1727: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ee790)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810ee790-ffffffff810ee7e7: find_numa_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool find_numa_distance(int distance);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f97d0)
Location: kernel/sched/topology.c:1488
Inline: True
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810f97d0-ffffffff810f9827: find_numa_distance (STB_GLOBAL)
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
