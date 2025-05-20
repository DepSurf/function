# Function: <code>load_direct_gdt</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103dc33)
Location: arch/x86/kernel/cpu/common.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
Direct callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8103d910-ffffffff8103d943: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810404d0)
Location: arch/x86/kernel/cpu/common.c:514
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff810404d0-ffffffff81040503: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041d40)
Location: arch/x86/kernel/cpu/common.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81041d40-ffffffff81041d73: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81043360)
Location: arch/x86/kernel/cpu/common.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81043360-ffffffff81043393: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045830)
Location: arch/x86/kernel/cpu/common.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81045830-ffffffff81045863: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045f80)
Location: arch/x86/kernel/cpu/common.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81045f80-ffffffff81045fb3: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a030)
Location: arch/x86/kernel/cpu/common.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8104a030-ffffffff8104a063: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810494d0)
Location: arch/x86/kernel/cpu/common.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff810494d0-ffffffff81049503: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ad30)
Location: arch/x86/kernel/cpu/common.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8104ad30-ffffffff8104ad63: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051da0)
Location: arch/x86/kernel/cpu/common.c:612
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81051da0-ffffffff81051df7: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d560)
Location: arch/x86/kernel/cpu/common.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8105d560-ffffffff8105d5de: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106ba20)
Location: arch/x86/kernel/cpu/common.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8106ba20-ffffffff8106bac1: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d3d0)
Location: arch/x86/kernel/cpu/common.c:701
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8106d3d0-ffffffff8106d471: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff838ce4cb)
Location: arch/x86/kernel/cpu/common.c:698
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
Direct callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81074550-ffffffff810745f1: load_direct_gdt (STB_GLOBAL)
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
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046100)
Location: arch/x86/kernel/cpu/common.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81046100-ffffffff81046133: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81036674)
Location: arch/x86/kernel/cpu/common.c:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff810353a0-ffffffff810353cc: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045f40)
Location: arch/x86/kernel/cpu/common.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81045f40-ffffffff81045f73: load_direct_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void load_direct_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047340)
Location: arch/x86/kernel/cpu/common.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81047340-ffffffff81047373: load_direct_gdt (STB_GLOBAL)
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
