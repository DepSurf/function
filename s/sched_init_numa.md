# Function: <code>sched_init_numa</code>

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
In kernel/sched/core.c (ffffffff81f7da3a)
Location: kernel/sched/core.c:6644
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
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
In kernel/sched/core.c (ffffffff81fa68fd)
Location: kernel/sched/core.c:6610
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
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
In kernel/sched/core.c (ffffffff81fe248a)
Location: kernel/sched/core.c:6707
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cbb60)
Location: kernel/sched/topology.c:1327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810cbb60-ffffffff810cc10c: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4390)
Location: kernel/sched/topology.c:1330
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810d4390-ffffffff810d49c2: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1325
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810dcf6f-ffffffff810dcf91: sched_init_numa.cold.17 (STB_LOCAL)
ffffffff810dbfa0-ffffffff810dc5af: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1529
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810e6bd5-ffffffff810e6bf7: sched_init_numa.cold.19 (STB_LOCAL)
ffffffff810e5bd0-ffffffff810e6207: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1554
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810ed866-ffffffff810ed888: sched_init_numa.cold (STB_LOCAL)
ffffffff810ec820-ffffffff810ece57: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810f9407-ffffffff810f9429: sched_init_numa.cold (STB_LOCAL)
ffffffff810f82c0-ffffffff810f88f7: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1540
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff811034f2-ffffffff81103514: sched_init_numa.cold (STB_LOCAL)
ffffffff811022d0-ffffffff811027a8: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1599
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff81bdce6d-ffffffff81bdce8f: sched_init_numa.cold (STB_LOCAL)
ffffffff81100ee0-ffffffff811013ce: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1633
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff81bcefd9-ffffffff81bceffb: sched_init_numa.cold (STB_LOCAL)
ffffffff811032a0-ffffffff81103753: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff81ca76f1-ffffffff81ca7728: sched_init_numa.cold (STB_LOCAL)
ffffffff811200a0-ffffffff81120635: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sched_init_numa(int offline_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1806
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/build_utility.c:sched_update_numa
```
**Symbols:**

```
ffffffff81e59490-ffffffff81e594c7: sched_init_numa.cold (STB_LOCAL)
ffffffff8114a230-ffffffff8114a7d9: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sched_init_numa(int offline_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1806
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/build_utility.c:sched_update_numa
```
**Symbols:**

```
ffffffff8205815d-ffffffff82058172: sched_init_numa.cold (STB_LOCAL)
ffffffff81178bf0-ffffffff8117915f: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sched_init_numa(int offline_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1813
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/build_utility.c:sched_update_numa
```
**Symbols:**

```
ffffffff820d6a3f-ffffffff820d6a54: sched_init_numa.cold (STB_LOCAL)
ffffffff811897e0-ffffffff81189d4f: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sched_init_numa(int offline_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1839
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/build_utility.c:sched_update_numa
```
**Symbols:**

```
ffffffff821b1cd5-ffffffff821b1cea: sched_init_numa.cold (STB_LOCAL)
ffffffff811980e0-ffffffff8119864f: sched_init_numa (STB_GLOBAL)
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
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015c8b8)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffff80001015c8b8-ffff80001015ced4: sched_init_numa (STB_GLOBAL)
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1277
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1160)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
c0000000001b1160-c0000000001b193c: sched_init_numa (STB_GLOBAL)
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1277
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810f2807-ffffffff810f2829: sched_init_numa.cold (STB_LOCAL)
ffffffff810f16c0-ffffffff810f1cf7: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810e2877-ffffffff810e2899: sched_init_numa.cold (STB_LOCAL)
ffffffff810e1730-ffffffff810e1d67: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810ef937-ffffffff810ef959: sched_init_numa.cold (STB_LOCAL)
ffffffff810ee7f0-ffffffff810eee27: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sched_init_numa();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1555
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810fa987-ffffffff810fa9a9: sched_init_numa.cold (STB_LOCAL)
ffffffff810f9830-ffffffff810f9e67: sched_init_numa (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offline_node</code>
</li>
</ul>
</details>
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
