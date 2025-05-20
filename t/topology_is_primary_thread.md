# Function: <code>topology_is_primary_thread</code>

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
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81059fe0)
Location: arch/x86/kernel/smpboot.c:278
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81059fe0-ffffffff8105a005: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fc60)
Location: arch/x86/kernel/smpboot.c:278
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8105fc60-ffffffff8105fc85: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063490)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81063490-ffffffff810634b5: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063b40)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81063b40-ffffffff81063b65: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a550)
Location: arch/x86/kernel/smpboot.c:284
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_event_init
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_wait_for_ap
```
**Symbols:**

```
ffffffff8106a550-ffffffff8106a575: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c220)
Location: arch/x86/kernel/smpboot.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_wait_for_ap
```
**Symbols:**

```
ffffffff8106c220-ffffffff8106c245: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106ccf0)
Location: arch/x86/kernel/smpboot.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8106ccf0-ffffffff8106cd15: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077ce0)
Location: arch/x86/kernel/smpboot.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81077ce0-ffffffff81077d25: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81086940)
Location: arch/x86/kernel/smpboot.c:273
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81086940-ffffffff8108698d: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81099f10)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81099f10-ffffffff81099f5d: topology_is_primary_thread (STB_GLOBAL)
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
In kernel/cpu.c (ffffffff810fab75)
Location: arch/x86/include/asm/topology.h:151
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpuhp_bringup_ap
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
In kernel/cpu.c (ffffffff81103f93)
Location: arch/x86/include/asm/topology.h:152
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpuhp_bringup_ap
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
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063630)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81063630-ffffffff81063655: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053940)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81053940-ffffffff81053965: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063ae0)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81063ae0-ffffffff81063b05: topology_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool topology_is_primary_thread(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810650a0)
Location: arch/x86/kernel/smpboot.c:271
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810650a0-ffffffff810650c5: topology_is_primary_thread (STB_GLOBAL)
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
