# Function: <code>load_current_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040338)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810663cb)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041076)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff8106615b)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040ac3)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff8106967b)
Location: arch/x86/include/asm/desc.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea46)
Location: arch/x86/include/asm/desc.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810688eb)
Location: arch/x86/include/asm/desc.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041733)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057747)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81043003)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a627)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104466b)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810602a7)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046c19)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063bae)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047399)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106425e)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810347f0)
Location: arch/x86/kernel/idt.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810347f0-ffffffff81034809: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81035000)
Location: arch/x86/kernel/idt.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff81035000-ffffffff81035019: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81036a40)
Location: arch/x86/kernel/idt.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff81036a40-ffffffff81036a59: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8103bd40)
Location: arch/x86/kernel/idt.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff8103bd40-ffffffff8103bd59: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81042db0)
Location: arch/x86/kernel/idt.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff81042db0-ffffffff81042de2: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8104c800)
Location: arch/x86/kernel/idt.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff8104c800-ffffffff8104c832: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8104d070)
Location: arch/x86/kernel/idt.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff8104d070-ffffffff8104d0a2: load_current_idt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void load_current_idt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810542f0)
Location: arch/x86/kernel/idt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff810542f0-ffffffff81054322: load_current_idt (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047519)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063d4e)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103669f)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105405e)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047359)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810641fe)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81048759)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810657be)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
