# Function: <code>load_fixmap_gdt</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103d950)
Location: arch/x86/kernel/cpu/common.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8103d950-ffffffff8103d985: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040540)
Location: arch/x86/kernel/cpu/common.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81040540-ffffffff81040567: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041db0)
Location: arch/x86/kernel/cpu/common.c:535
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81041db0-ffffffff81041dd7: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810433d0)
Location: arch/x86/kernel/cpu/common.c:535
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff810433d0-ffffffff810433f7: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810458d0)
Location: arch/x86/kernel/cpu/common.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810458d0-ffffffff810458f7: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046020)
Location: arch/x86/kernel/cpu/common.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81046020-ffffffff81046047: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a0a0)
Location: arch/x86/kernel/cpu/common.c:604
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8104a0a0-ffffffff8104a0c7: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049540)
Location: arch/x86/kernel/cpu/common.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81049540-ffffffff81049567: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ad70)
Location: arch/x86/kernel/cpu/common.c:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8104ad70-ffffffff8104ad97: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051e00)
Location: arch/x86/kernel/cpu/common.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81051e00-ffffffff81051e27: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d5e0)
Location: arch/x86/kernel/cpu/common.c:731
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8105d5e0-ffffffff8105d636: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106bae0)
Location: arch/x86/kernel/cpu/common.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8106bae0-ffffffff8106bb59: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d490)
Location: arch/x86/kernel/cpu/common.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8106d490-ffffffff8106d509: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810763fe)
Location: arch/x86/kernel/cpu/common.c:709
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810744c0-ffffffff81074539: load_fixmap_gdt (STB_GLOBAL)
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
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810461a0)
Location: arch/x86/kernel/cpu/common.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff810461a0-ffffffff810461c7: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810369c5)
Location: arch/x86/kernel/cpu/common.c:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81035460-ffffffff81035480: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045fe0)
Location: arch/x86/kernel/cpu/common.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81045fe0-ffffffff81046007: load_fixmap_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void load_fixmap_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810473e0)
Location: arch/x86/kernel/cpu/common.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff810473e0-ffffffff81047407: load_fixmap_gdt (STB_GLOBAL)
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
