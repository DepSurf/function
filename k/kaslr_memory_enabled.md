# Function: <code>kaslr_memory_enabled</code>

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
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/mm/kaslr.c:78
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/mm/kaslr.c:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/mm/kaslr.c:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/mm/kaslr.c:78
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff826ef513)
Location: arch/x86/mm/kaslr.c:67
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828a6201)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828be7f3)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828c4c95)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init.c (ffffffff82ce5648)
Location: arch/x86/include/asm/setup.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff82ce7ebe)
Location: arch/x86/include/asm/setup.h:86
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff82fd2e9e)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff82fd58b5)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff831ddaed)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff831e0360)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff832c0d0d)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff832c39eb)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff83473302)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff834762ea)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff83e9ab9d)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff83e9f22c)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff836be595)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff836c33ac)
Location: arch/x86/include/asm/setup.h:90
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/init.c (ffffffff838ef055)
Location: arch/x86/include/asm/setup.h:88
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff838f3f8c)
Location: arch/x86/include/asm/setup.h:88
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828afc2d)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828a7e1f)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828c2b2c)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff828c5cb5)
Location: arch/x86/mm/kaslr.c:68
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
</ul>

## Differences
