# Function: <code>native_load_gs_index</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fd80)
Location: arch/x86/include/asm/special_insns.h:135
Inline: False
```
**Symbols:**

```
ffffffff8107fd80-ffffffff8107fdab: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f9a0)
Location: arch/x86/include/asm/special_insns.h:137
Inline: False
```
**Symbols:**

```
ffffffff8107f9a0-ffffffff8107f9cb: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080ab0)
Location: arch/x86/include/asm/special_insns.h:137
Inline: False
```
**Symbols:**

```
ffffffff81080ab0-ffffffff81080ae3: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108fa00)
Location: arch/x86/include/asm/special_insns.h:125
Inline: False
```
**Symbols:**

```
ffffffff8108fa00-ffffffff8108fa33: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0700)
Location: arch/x86/include/asm/special_insns.h:125
Inline: False
```
**Symbols:**

```
ffffffff810a0700-ffffffff810a0732: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b8370)
Location: arch/x86/include/asm/special_insns.h:125
Inline: False
```
**Symbols:**

```
ffffffff810b8370-ffffffff810b83b1: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb6e0)
Location: arch/x86/include/asm/gsseg.h:28
Inline: True
```
**Symbols:**

```
ffffffff810bb6e0-ffffffff810bb722: native_load_gs_index.part.0 (STB_LOCAL)
ffffffff810bb740-ffffffff810bb761: native_load_gs_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void native_load_gs_index(unsigned int selector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2af0)
Location: arch/x86/include/asm/gsseg.h:28
Inline: True
```
**Symbols:**

```
ffffffff810c2af0-ffffffff810c2b32: native_load_gs_index.part.0 (STB_LOCAL)
ffffffff810c2b50-ffffffff810c2b71: native_load_gs_index (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/tls.c:do_set_thread_area
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
  - kernel/fork.c:mm_release
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81c00ed0-ffffffff81c00ee4: native_load_gs_index (STB_GLOBAL)
```
</details>
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
