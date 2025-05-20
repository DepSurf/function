# Function: <code>arch_match_cpu_phys_id</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f370)
Location: arch/x86/kernel/apic/apic.c:2337
Inline: False
```
**Symbols:**

```
ffffffff8106f370-ffffffff8106f38c: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106fea0)
Location: arch/x86/kernel/apic/apic.c:2345
Inline: False
```
**Symbols:**

```
ffffffff8106fea0-ffffffff8106febc: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107b8d0)
Location: arch/x86/kernel/apic/apic.c:2342
Inline: False
```
**Symbols:**

```
ffffffff8107b8d0-ffffffff8107b90f: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8108aa90)
Location: arch/x86/kernel/apic/apic.c:2350
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
**Symbols:**

```
ffffffff8108aa90-ffffffff8108aad7: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109eb70)
Location: arch/x86/kernel/apic/apic.c:2384
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
**Symbols:**

```
ffffffff8109eb70-ffffffff8109ebb7: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a1b50)
Location: arch/x86/kernel/apic/apic.c:2387
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
**Symbols:**

```
ffffffff810a1b50-ffffffff810a1b97: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a8ba0)
Location: arch/x86/kernel/apic/apic.c:2323
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
**Symbols:**

```
ffffffff810a8ba0-ffffffff810a8be6: arch_match_cpu_phys_id (STB_GLOBAL)
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff80001008f620)
Location: arch/arm64/kernel/setup.c:100
Inline: False
Direct callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
**Symbols:**

```
ffff80001008f620-ffff80001008f664: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/devtree.c (c0315a8c)
Location: arch/arm/kernel/devtree.c:186
Inline: False
Direct callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
**Symbols:**

```
c0315a8c-c0315ac4: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/prom.c (c00000000002c4c0)
Location: arch/powerpc/kernel/prom.c:889
Inline: False
Direct callers:
  - drivers/of/base.c:__of_find_n_match_cpu_property
  - drivers/of/base.c:__of_find_n_match_cpu_property
```
**Symbols:**

```
c00000000002c4c0-c00000000002c528: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smp.c (ffffffe0000b7d64)
Location: arch/riscv/kernel/smp.c:66
Inline: False
Direct callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
**Symbols:**

```
ffffffe0000b7d64-ffffffe0000b7da0: arch_match_cpu_phys_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
