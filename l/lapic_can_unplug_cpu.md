# Function: <code>lapic_can_unplug_cpu</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c710)
Location: arch/x86/kernel/apic/vector.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff8105c710-ffffffff8105c7b1: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff8105f7f0-ffffffff8105f825: lapic_can_unplug_cpu.cold.26 (STB_LOCAL)
ffffffff8105f760-ffffffff8105f7da: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81065460-ffffffff81065495: lapic_can_unplug_cpu.cold.25 (STB_LOCAL)
ffffffff810653d0-ffffffff8106544a: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81068b7a-ffffffff81068bb2: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81068ab0-ffffffff81068b30: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81069500-ffffffff81069538: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81069420-ffffffff810694a0: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810704da-ffffffff81070512: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81070400-ffffffff81070480: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81bd70b8-ffffffff81bd70f0: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81071960-ffffffff810719e0: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1113
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81bc9270-ffffffff81bc92a8: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81072460-ffffffff810724e0: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1113
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81c9dd5c-ffffffff81c9dd94: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff8107e340-ffffffff8107e3c0: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1113
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81e4d1e7-ffffffff81e4d236: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff8108d9f0-ffffffff8108da58: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a2140)
Location: arch/x86/kernel/apic/vector.c:1109
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810a2140-ffffffff810a21e9: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a5120)
Location: arch/x86/kernel/apic/vector.c:1109
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810a5120-ffffffff810a51c9: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810ac1b0)
Location: arch/x86/kernel/apic/vector.c:1167
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810ac1b0-ffffffff810ac259: lapic_can_unplug_cpu (STB_GLOBAL)
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
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81068ff0-ffffffff81069028: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81068f10-ffffffff81068f90: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff81059360-ffffffff81059398: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff81059280-ffffffff81059300: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810694a0-ffffffff810694d8: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff810693c0-ffffffff81069440: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int lapic_can_unplug_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff8106ab9e-ffffffff8106abd6: lapic_can_unplug_cpu.cold (STB_LOCAL)
ffffffff8106aac0-ffffffff8106ab3e: lapic_can_unplug_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
