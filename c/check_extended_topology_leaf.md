# Function: <code>check_extended_topology_leaf</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff810454c0)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
```
**Symbols:**

```
ffffffff810454c0-ffffffff8104552c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff81045c10)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
```
**Symbols:**

```
ffffffff81045c10-ffffffff81045c7c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff81049b9b)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff81049a30-ffffffff81049a9c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8104901b)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff81048eb0-ffffffff81048f1c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8104a8eb)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff8104a780-ffffffff8104a7ec: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8105180b)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff810516a0-ffffffff8105170c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8105cca0)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff8105cca0-ffffffff8105cd31: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8106b030)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff8106b030-ffffffff8106b0c1: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff8106c9a0)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
**Symbols:**

```
ffffffff8106c9a0-ffffffff8106ca3b: check_extended_topology_leaf (STB_LOCAL)
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
In arch/x86/kernel/cpu/topology.c (ffffffff81073de9)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
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
<summary>In <code>aws</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff81045d90)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
```
**Symbols:**

```
ffffffff81045d90-ffffffff81045dfc: check_extended_topology_leaf (STB_LOCAL)
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
In arch/x86/kernel/cpu/topology.c (ffffffff81035161)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff81045bd0)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
```
**Symbols:**

```
ffffffff81045bd0-ffffffff81045c3c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/topology.c (ffffffff81046fd0)
Location: arch/x86/kernel/cpu/topology.c:35
Inline: False
```
**Symbols:**

```
ffffffff81046fd0-ffffffff8104703c: check_extended_topology_leaf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
