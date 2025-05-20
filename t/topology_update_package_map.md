# Function: <code>topology_update_package_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int apicid, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050f60)
Location: arch/x86/kernel/smpboot.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
**Symbols:**

```
ffffffff81050f60-ffffffff81051068: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int apicid, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051120)
Location: arch/x86/kernel/smpboot.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_init_package_map
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
**Symbols:**

```
ffffffff81051120-ffffffff810511f0: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053a60)
Location: arch/x86/kernel/smpboot.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81053a60-ffffffff81053b19: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810533c0)
Location: arch/x86/kernel/smpboot.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810533c0-ffffffff8105347a: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057170)
Location: arch/x86/kernel/smpboot.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81057170-ffffffff810571d9: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8105b64e-ffffffff8105b667: topology_update_package_map.cold.8 (STB_LOCAL)
ffffffff8105a030-ffffffff8105a087: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810612d8-ffffffff810612f1: topology_update_package_map.cold.10 (STB_LOCAL)
ffffffff8105fcb0-ffffffff8105fd07: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810649b1-ffffffff810649ca: topology_update_package_map.cold (STB_LOCAL)
ffffffff810634e0-ffffffff81063537: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81065031-ffffffff8106504a: topology_update_package_map.cold (STB_LOCAL)
ffffffff81063b90-ffffffff81063be7: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:validate_apic_and_package_id
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8106b984-ffffffff8106b99d: topology_update_package_map.cold (STB_LOCAL)
ffffffff8106a5a0-ffffffff8106a5f7: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:validate_apic_and_package_id
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81bd68f1-ffffffff81bd690a: topology_update_package_map.cold (STB_LOCAL)
ffffffff8106c270-ffffffff8106c2c7: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81bc8acb-ffffffff81bc8ae4: topology_update_package_map.cold (STB_LOCAL)
ffffffff8106cd40-ffffffff8106cd97: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81c9d416-ffffffff81c9d42f: topology_update_package_map.cold (STB_LOCAL)
ffffffff81077d50-ffffffff81077dc9: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81e4c8a7-ffffffff81e4c8c0: topology_update_package_map.cold (STB_LOCAL)
ffffffff810869b0-ffffffff81086a35: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81099fa0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81099fa0-ffffffff8109a037: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109d3c0)
Location: arch/x86/kernel/smpboot.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff8109d3c0-ffffffff8109d457: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a48d0)
Location: arch/x86/kernel/smpboot.c:381
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
**Symbols:**

```
ffffffff810a48d0-ffffffff810a49ce: topology_update_package_map (STB_GLOBAL)
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81064b21-ffffffff81064b3a: topology_update_package_map.cold (STB_LOCAL)
ffffffff81063680-ffffffff810636d7: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81054df6-ffffffff81054e0f: topology_update_package_map.cold (STB_LOCAL)
ffffffff81053990-ffffffff810539e7: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff81064fd1-ffffffff81064fea: topology_update_package_map.cold (STB_LOCAL)
ffffffff81063b30-ffffffff81063b87: topology_update_package_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
```
**Symbols:**

```
ffffffff810665b1-ffffffff810665ca: topology_update_package_map.cold (STB_LOCAL)
ffffffff810650f0-ffffffff81065147: topology_update_package_map (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int pkg</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int apicid</code>
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
