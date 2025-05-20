# Function: <code>topology_smt_supported</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105a010)
Location: arch/x86/kernel/smpboot.c:286
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology_early
```
**Symbols:**

```
ffffffff8105a010-ffffffff8105a025: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fc90)
Location: arch/x86/kernel/smpboot.c:286
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff8105fc90-ffffffff8105fca5: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810634c0)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff810634c0-ffffffff810634d5: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063b70)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81063b70-ffffffff81063b85: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a580)
Location: arch/x86/kernel/smpboot.c:292
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_event_init
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff8106a580-ffffffff8106a595: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c250)
Location: arch/x86/kernel/smpboot.c:287
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff8106c250-ffffffff8106c265: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106cd20)
Location: arch/x86/kernel/smpboot.c:286
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff8106cd20-ffffffff8106cd35: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077d30)
Location: arch/x86/kernel/smpboot.c:285
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81077d30-ffffffff81077d45: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81086990)
Location: arch/x86/kernel/smpboot.c:281
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81086990-ffffffff810869a9: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81099f70)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81099f70-ffffffff81099f89: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109d390)
Location: arch/x86/kernel/smpboot.c:332
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff8109d390-ffffffff8109d3a9: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063660)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81063660-ffffffff81063675: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053970)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81053970-ffffffff81053985: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063b10)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff81063b10-ffffffff81063b25: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool topology_smt_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810650d0)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_smt_check_topology
```
**Symbols:**

```
ffffffff810650d0-ffffffff810650e5: topology_smt_supported (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
