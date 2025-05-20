# Function: <code>get_xsave_field_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b7c0)
Location: arch/x86/kernel/fpu/xstate.c:739
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8103b7c0-ffffffff8103b805: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b2b0)
Location: arch/x86/kernel/fpu/xstate.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8103b2b0-ffffffff8103b2f3: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ab90)
Location: arch/x86/kernel/fpu/xstate.c:859
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8103ab90-ffffffff8103abd3: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a00)
Location: arch/x86/kernel/fpu/xstate.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff81038a00-ffffffff81038a48: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ab70)
Location: arch/x86/kernel/fpu/xstate.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8103ab70-ffffffff8103abb8: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c070)
Location: arch/x86/kernel/fpu/xstate.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8103c070-ffffffff8103c0b3: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xsave_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d4f0)
Location: arch/x86/kernel/fpu/xstate.c:891
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff8103d4f0-ffffffff8103d533: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fda0)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff8103fda0-ffffffff8103fdd8: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810404c0)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff810404c0-ffffffff810404f8: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043840)
Location: arch/x86/kernel/fpu/xstate.c:935
Inline: False
```
**Symbols:**

```
ffffffff81043840-ffffffff81043878: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810438f0)
Location: arch/x86/kernel/fpu/xstate.c:975
Inline: False
```
**Symbols:**

```
ffffffff810438f0-ffffffff81043928: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045140)
Location: arch/x86/kernel/fpu/xstate.c:1010
Inline: False
```
**Symbols:**

```
ffffffff81045140-ffffffff81045178: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040640)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81040640-ffffffff81040678: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fe20)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff8102fe20-ffffffff8102fe58: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040480)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81040480-ffffffff810404b8: get_xsave_field_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const void *get_xsave_field_ptr(int xfeature_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041850)
Location: arch/x86/kernel/fpu/xstate.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81041850-ffffffff81041888: get_xsave_field_ptr (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int xfeature_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>int xsave_state</code>
</li>
</ul>
</details>
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
