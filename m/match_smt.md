# Function: <code>match_smt</code>

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
In arch/x86/kernel/smpboot.c (ffffffff8105118d)
Location: arch/x86/kernel/smpboot.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81051295)
Location: arch/x86/kernel/smpboot.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81053bdd)
Location: arch/x86/kernel/smpboot.c:430
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81053546)
Location: arch/x86/kernel/smpboot.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff8105735a)
Location: arch/x86/kernel/smpboot.c:370
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff8105a31e)
Location: arch/x86/kernel/smpboot.c:390
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff8105ff9e)
Location: arch/x86/kernel/smpboot.c:390
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81063793)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81063e43)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a85b)
Location: arch/x86/kernel/smpboot.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c52b)
Location: arch/x86/kernel/smpboot.c:435
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d07f)
Location: arch/x86/kernel/smpboot.c:434
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8107817b)
Location: arch/x86/kernel/smpboot.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool match_smt(struct cpuinfo_x86 *c, struct cpuinfo_x86 *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81086110)
Location: arch/x86/kernel/smpboot.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
**Symbols:**

```
ffffffff81086110-ffffffff810862a8: match_smt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool match_smt(struct cpuinfo_x86 *c, struct cpuinfo_x86 *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81099430)
Location: arch/x86/kernel/smpboot.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
**Symbols:**

```
ffffffff81099430-ffffffff810995c8: match_smt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool match_smt(struct cpuinfo_x86 *c, struct cpuinfo_x86 *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109c810)
Location: arch/x86/kernel/smpboot.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
**Symbols:**

```
ffffffff8109c810-ffffffff8109c9a8: match_smt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool match_smt(struct cpuinfo_x86 *c, struct cpuinfo_x86 *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a3d60)
Location: arch/x86/kernel/smpboot.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
**Symbols:**

```
ffffffff810a3d60-ffffffff810a3ed7: match_smt (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063933)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81053c43)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff81063de3)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
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
In arch/x86/kernel/smpboot.c (ffffffff810653a3)
Location: arch/x86/kernel/smpboot.c:427
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
