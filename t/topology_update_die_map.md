# Function: <code>topology_update_die_map</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810649ca-ffffffff810649e3: topology_update_die_map.cold (STB_LOCAL)
ffffffff81063540-ffffffff8106359a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8106504a-ffffffff81065063: topology_update_die_map.cold (STB_LOCAL)
ffffffff81063bf0-ffffffff81063c4a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:validate_apic_and_package_id
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8106b99d-ffffffff8106b9b6: topology_update_die_map.cold (STB_LOCAL)
ffffffff8106a600-ffffffff8106a65a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:validate_apic_and_package_id
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81bd690a-ffffffff81bd6923: topology_update_die_map.cold (STB_LOCAL)
ffffffff8106c2d0-ffffffff8106c32a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81bc8ae4-ffffffff81bc8afd: topology_update_die_map.cold (STB_LOCAL)
ffffffff8106cda0-ffffffff8106cdfa: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81c9d42f-ffffffff81c9d448: topology_update_die_map.cold (STB_LOCAL)
ffffffff81077dd0-ffffffff81077e49: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81e4c8c0-ffffffff81e4c8d9: topology_update_die_map.cold (STB_LOCAL)
ffffffff81086a40-ffffffff81086ac5: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109a050)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8109a050-ffffffff8109a0e7: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109d470)
Location: arch/x86/kernel/smpboot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8109d470-ffffffff8109d5db: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a49e0)
Location: arch/x86/kernel/smpboot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
**Symbols:**

```
ffffffff810a49e0-ffffffff810a4c27: topology_update_die_map (STB_GLOBAL)
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
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81064b3a-ffffffff81064b53: topology_update_die_map.cold (STB_LOCAL)
ffffffff810636e0-ffffffff8106373a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81054e0f-ffffffff81054e28: topology_update_die_map.cold (STB_LOCAL)
ffffffff810539f0-ffffffff81053a4a: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81064fea-ffffffff81065003: topology_update_die_map.cold (STB_LOCAL)
ffffffff81063b90-ffffffff81063bea: topology_update_die_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810665ca-ffffffff810665e3: topology_update_die_map.cold (STB_LOCAL)
ffffffff81065150-ffffffff810651aa: topology_update_die_map (STB_GLOBAL)
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
