# Function: <code>clear_rdrand_cpuid_bit</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a23a)
Location: arch/x86/kernel/cpu/amd.c:823
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104a170-ffffffff8104a25a: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104ac90-ffffffff8104acc0: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104abca)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104ab00-ffffffff8104abea: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104b690-ffffffff8104b6c0: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104edb6)
Location: arch/x86/kernel/cpu/amd.c:851
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104ed30-ffffffff8104ee1a: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104fead-ffffffff8104fedd: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e076)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104dff0-ffffffff8104e0da: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff81bd53d2-ffffffff81bd5402: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fdf6)
Location: arch/x86/kernel/cpu/amd.c:820
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104fd70-ffffffff8104fe5a: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff81bc7808-ffffffff81bc7838: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff810580c4)
Location: arch/x86/kernel/cpu/amd.c:824
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81058030-ffffffff81058144: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff81c9b238-ffffffff81c9b2ab: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8106461b)
Location: arch/x86/kernel/cpu/amd.c:800
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81064560-ffffffff810646ac: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff81e4a773-ffffffff81e4a7e6: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8107384b)
Location: arch/x86/kernel/cpu/amd.c:798
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81073790-ffffffff81073902: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff82052be9-ffffffff82052c2c: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff810756fb)
Location: arch/x86/kernel/cpu/amd.c:870
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81075640-ffffffff810757b2: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff820d10ca-ffffffff820d110d: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8107cb5b)
Location: arch/x86/kernel/cpu/amd.c:864
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8107caa0-ffffffff8107cc12: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff821abbe7-ffffffff821abc2a: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ad3a)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104ac70-ffffffff8104ad5a: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104b800-ffffffff8104b830: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81039dc3)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81039d50-ffffffff81039de6: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8103aca7-ffffffff8103acd7: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ab7a)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104aab0-ffffffff8104ab9a: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104b640-ffffffff8104b670: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104bf8a)
Location: arch/x86/kernel/cpu/amd.c:825
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104bec0-ffffffff8104bfaa: clear_rdrand_cpuid_bit (STB_LOCAL)
ffffffff8104ca50-ffffffff8104ca80: clear_rdrand_cpuid_bit.cold (STB_LOCAL)
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
