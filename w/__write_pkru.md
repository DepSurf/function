# Function: <code>__write_pkru</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b358)
Location: arch/x86/include/asm/special_insns.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac2a)
Location: arch/x86/include/asm/special_insns.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b782)
Location: arch/x86/include/asm/special_insns.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a93)
Location: arch/x86/include/asm/special_insns.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81079f42)
Location: arch/x86/include/asm/special_insns.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac03)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810801b2)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c110)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810832b4)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d590)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81089e64)
Location: arch/x86/include/asm/special_insns.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/process_64.c (ffffffff8102f629)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe6c)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dbfa)
Location: arch/x86/include/asm/special_insns.h:118
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
In arch/x86/kernel/process_64.c (ffffffff8102ff89)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104058c)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e85a)
Location: arch/x86/include/asm/special_insns.h:104
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
In arch/x86/kernel/process_64.c (ffffffff81032829)
Location: arch/x86/include/asm/special_insns.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043930)
Location: arch/x86/include/asm/special_insns.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949dd)
Location: arch/x86/include/asm/special_insns.h:105
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
In arch/x86/kernel/process_64.c (ffffffff8103347d)
Location: arch/x86/include/asm/special_insns.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810439e0)
Location: arch/x86/include/asm/special_insns.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093dcd)
Location: arch/x86/include/asm/special_insns.h:107
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
In arch/x86/kernel/process_64.c (ffffffff81034f75)
Location: arch/x86/include/asm/special_insns.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045224)
Location: arch/x86/include/asm/special_insns.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8109478d)
Location: arch/x86/include/asm/special_insns.h:107
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810300e9)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104070c)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d81a)
Location: arch/x86/include/asm/special_insns.h:104
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
In arch/x86/kernel/process_64.c (ffffffff8101fb5e)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102feec)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c34a)
Location: arch/x86/include/asm/special_insns.h:104
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
In arch/x86/kernel/process_64.c (ffffffff8102ff49)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104054c)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7ca)
Location: arch/x86/include/asm/special_insns.h:104
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
In arch/x86/kernel/process_64.c (ffffffff81030d99)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041922)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb91)
Location: arch/x86/include/asm/special_insns.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
</ul>

## Differences
