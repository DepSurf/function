# Function: <code>write_pkru</code>

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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b343)
Location: arch/x86/include/asm/pgtable.h:110
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac14)
Location: arch/x86/include/asm/pgtable.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b777)
Location: arch/x86/include/asm/pgtable.h:110
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a86)
Location: arch/x86/include/asm/pgtable.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81079f37)
Location: arch/x86/include/asm/pgtable.h:122
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103abf6)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810801a7)
Location: arch/x86/include/asm/pgtable.h:132
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c103)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810832a9)
Location: arch/x86/include/asm/pgtable.h:132
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d583)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81089e59)
Location: arch/x86/include/asm/pgtable.h:134
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe2f)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dbc0)
Location: arch/x86/include/asm/pgtable.h:136
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8104054f)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e820)
Location: arch/x86/include/asm/pgtable.h:136
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810438f0)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949a0)
Location: arch/x86/include/asm/pgtable.h:138
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810439a0)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093d90)
Location: arch/x86/include/asm/pgtable.h:137
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810451e4)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81094750)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b6c7)
Location: arch/x86/include/asm/pkru.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8105639e)
Location: arch/x86/include/asm/pkru.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064049)
Location: arch/x86/include/asm/pkru.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065999)
Location: arch/x86/include/asm/pkru.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106cdf9)
Location: arch/x86/include/asm/pkru.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810406cf)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7e0)
Location: arch/x86/include/asm/pgtable.h:136
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8102feaf)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c310)
Location: arch/x86/include/asm/pgtable.h:136
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8104050f)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d790)
Location: arch/x86/include/asm/pgtable.h:136
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810418df)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb50)
Location: arch/x86/include/asm/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
</ul>

## Differences
