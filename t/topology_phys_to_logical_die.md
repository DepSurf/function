# Function: <code>topology_phys_to_logical_die</code>

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
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81062f80)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81062f80-ffffffff8106300d: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063630)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81063630-ffffffff810636bd: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810697f0)
Location: arch/x86/kernel/smpboot.c:320
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff810697f0-ffffffff8106987d: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b400)
Location: arch/x86/kernel/smpboot.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff8106b400-ffffffff8106b48d: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106be90)
Location: arch/x86/kernel/smpboot.c:314
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff8106be90-ffffffff8106bf27: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81076a10)
Location: arch/x86/kernel/smpboot.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81076a10-ffffffff81076b03: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810858c0)
Location: arch/x86/kernel/smpboot.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff810858c0-ffffffff810859c8: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810995e0)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff810995e0-ffffffff810996f7: topology_phys_to_logical_die (STB_GLOBAL)
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
In arch/x86/kernel/smpboot.c (ffffffff8109d48e)
Location: arch/x86/kernel/smpboot.c:364
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
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
In arch/x86/kernel/smpboot.c (ffffffff810a49f5)
Location: arch/x86/kernel/smpboot.c:364
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
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
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063120)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81063120-ffffffff810631ad: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053430)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81053430-ffffffff810534bd: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810635d0)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff810635d0-ffffffff8106365d: topology_phys_to_logical_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int topology_phys_to_logical_die(unsigned int die_id, unsigned int cur_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064b90)
Location: arch/x86/kernel/smpboot.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_die_map
```
**Symbols:**

```
ffffffff81064b90-ffffffff81064c1d: topology_phys_to_logical_die (STB_GLOBAL)
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
