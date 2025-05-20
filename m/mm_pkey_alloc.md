# Function: <code>mm_pkey_alloc</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8107b65d)
Location: arch/x86/include/asm/pkeys.h:65
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff811f55f0)
Location: arch/x86/include/asm/pkeys.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff81079e18)
Location: arch/x86/include/asm/pkeys.h:65
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff812003c2)
Location: arch/x86/include/asm/pkeys.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff81080088)
Location: arch/x86/include/asm/pkeys.h:66
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff81218b62)
Location: arch/x86/include/asm/pkeys.h:66
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108319b)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8123957d)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff81089d4b)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8124d1ad)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108daac)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8125f4cd)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108e70c)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8126dcdd)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8109487c)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8129e04d)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff81093c6c)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff812a93df)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8109462c)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff812ae86c)
Location: arch/x86/include/asm/pkeys.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff810a45b5)
Location: arch/x86/include/asm/pkeys.h:84
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff812f000e)
Location: arch/x86/include/asm/pkeys.h:84
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff810b8e0d)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff81353516)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff810d46ef)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff813cd816)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff810d7c19)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff81402179)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff810e0499)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8142e7a9)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108d6cc)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8126632d)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8107c1fc)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff8125877d)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108d67c)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff812640cd)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In arch/x86/mm/pkeys.c (ffffffff8108fa3c)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/mprotect.c (ffffffff81273a8d)
Location: arch/x86/include/asm/pkeys.h:81
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
</details>
</li>
</ul>

## Differences
