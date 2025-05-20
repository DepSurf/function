# Function: <code>kaslr_enabled</code>

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
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:71
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: arch/x86/include/asm/setup.h:71
Inline: True
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
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
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
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/setup.h:72
Inline: True
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
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:71
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: arch/x86/include/asm/setup.h:71
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/setup.h:71
Inline: True
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
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:75
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: arch/x86/include/asm/setup.h:75
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/setup.h:75
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff81033905)
Location: arch/x86/include/asm/setup.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff810694d5)
Location: arch/x86/include/asm/setup.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff826ef513)
Location: arch/x86/include/asm/setup.h:75
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81034c65)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8106f225)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828a6201)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81036bc3)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff81073308)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828be7f3)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81037394)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff810742c8)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828c4c95)
Location: arch/x86/include/asm/setup.h:76
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
In arch/x86/kernel/setup.c (ffffffff81039243)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8107b5e8)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff82ce5648)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff82ce7ebe)
Location: arch/x86/include/asm/setup.h:76
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
In arch/x86/kernel/setup.c (ffffffff81bd3af1)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8107b548)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff82fd2e9e)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff82fd58b5)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff81bc5f63)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8107c768)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff831ddaed)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff831e0360)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff81c98e51)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8108a888)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff832c0d0d)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff832c39eb)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff81e483fc)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff8109ae18)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff83473302)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff834762ea)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff81053945)
Location: arch/x86/include/asm/setup.h:80
Inline: True
```
```
In arch/x86/kernel/module.c (ffffffff810b18b8)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff83e9ab9d)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/kaslr.c (ffffffff83e9f22c)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff81054925)
Location: arch/x86/include/asm/setup.h:80
Inline: True
```
```
In arch/x86/kernel/module.c (ffffffff810b48f8)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff836be595)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff836bfd75)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In arch/x86/mm/kaslr.c (ffffffff836c33ac)
Location: arch/x86/include/asm/setup.h:80
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
In arch/x86/kernel/setup.c (ffffffff8105bb65)
Location: arch/x86/include/asm/setup.h:78
Inline: True
```
```
In arch/x86/kernel/module.c (ffffffff810bbd58)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/init.c (ffffffff838ef055)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0895)
Location: arch/x86/include/asm/setup.h:78
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In arch/x86/mm/kaslr.c (ffffffff838f3f8c)
Location: arch/x86/include/asm/setup.h:78
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff810374f4)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff810732c8)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828afc2d)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81026ed4)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff81063348)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828a7e1f)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81037354)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff81073278)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828c2b2c)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/kernel/setup.c (ffffffff81038354)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/module.c (ffffffff810752d8)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff828c5cb5)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
</ul>

## Differences
