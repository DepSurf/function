# Function: <code>wrpkru</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f632)
Location: arch/x86/include/asm/special_insns.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe75)
Location: arch/x86/include/asm/special_insns.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dc03)
Location: arch/x86/include/asm/special_insns.h:106
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/process_64.c (ffffffff8102ff92)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040595)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e863)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032832)
Location: arch/x86/include/asm/special_insns.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043939)
Location: arch/x86/include/asm/special_insns.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949e6)
Location: arch/x86/include/asm/special_insns.h:93
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033486)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810439e9)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093dd6)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034f7e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104522d)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81094796)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a44c)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81047eae)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049a4b)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b6d9)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81052aaa)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810414be)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8105113e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053bd6)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810563af)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e510)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104aba4)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8105e71e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061676)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106405a)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cb06)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b3e4)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8105fe0e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062f4a)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810659aa)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e4cb)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052654)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81066f0e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a236)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106ce0a)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075796)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/process_64.c (ffffffff810300f2)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040715)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d823)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/process_64.c (ffffffff8101fb67)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fef5)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c353)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/process_64.c (ffffffff8102ff52)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040555)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7d3)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/process_64.c (ffffffff81030da2)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104192b)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb9a)
Location: arch/x86/include/asm/special_insns.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
</ul>

## Differences
