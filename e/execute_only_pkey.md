# Function: <code>execute_only_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81077974)
Location: arch/x86/include/asm/pkeys.h:15
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff811e3c70)
Location: arch/x86/include/asm/pkeys.h:15
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8107b72d)
Location: arch/x86/include/asm/pkeys.h:14
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff811f3c50)
Location: arch/x86/include/asm/pkeys.h:14
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff81079eeb)
Location: arch/x86/include/asm/pkeys.h:14
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff811fed62)
Location: arch/x86/include/asm/pkeys.h:14
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108015b)
Location: arch/x86/include/asm/pkeys.h:15
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff812172d9)
Location: arch/x86/include/asm/pkeys.h:15
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108324a)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81238291)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff81089dfa)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff8124bc77)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108db7a)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff8125e0fc)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108e7da)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff8126c8d8)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff81094964)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff8129c6ac)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff81093d54)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff812a79db)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8109471f)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff812ad6ff)
Location: arch/x86/include/asm/pkeys.h:27
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff810a46c8)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff812eeea0)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff810b8f2c)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81352275)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff810d484c)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff813cc24f)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff810d7d5c)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81400bbf)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff810e05dc)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff8142d20a)
Location: arch/x86/include/asm/pkeys.h:25
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108d79a)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81264f28)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8107c2ca)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81257348)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108d74a)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81262cc8)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
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
In arch/x86/mm/pkeys.c (ffffffff8108fb0a)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/mmap.c (ffffffff81272688)
Location: arch/x86/include/asm/pkeys.h:22
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
</details>
</li>
</ul>

## Differences
