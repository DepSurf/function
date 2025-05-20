# Function: <code>e820__range_update</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab7bf)
Location: arch/x86/kernel/e820.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
```
**Symbols:**

```
ffffffff820ab7bf-ffffffff820ab7e1: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1f95)
Location: arch/x86/kernel/e820.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
```
**Symbols:**

```
ffffffff826b1f95-ffffffff826b1fb7: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db661)
Location: arch/x86/kernel/e820.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
```
**Symbols:**

```
ffffffff826db661-ffffffff826db683: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891a48)
Location: arch/x86/kernel/e820.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
```
**Symbols:**

```
ffffffff82891a48-ffffffff82891a6a: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8fa5)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
```
**Symbols:**

```
ffffffff828a8fa5-ffffffff828a8fc7: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac009)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828ac009-ffffffff828ac02b: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd1319)
Location: arch/x86/kernel/e820.c:516
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82cd1319-ffffffff82cd133b: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbd169)
Location: arch/x86/kernel/e820.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82fbd169-ffffffff82fbd18b: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c787a)
Location: arch/x86/kernel/e820.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff831c787a-ffffffff831c789c: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a8a61)
Location: arch/x86/kernel/e820.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff832a8a61-ffffffff832a8a83: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83458041)
Location: arch/x86/kernel/e820.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff83458041-ffffffff83458072: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e77cd6)
Location: arch/x86/kernel/e820.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff83e77080-ffffffff83e770b1: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8369a148)
Location: arch/x86/kernel/e820.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff836990e0-ffffffff83699111: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c9ec8)
Location: arch/x86/kernel/e820.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff838c8e60-ffffffff838c8e91: e820__range_update (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8289a01b)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff8289a01b-ffffffff8289a03d: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828922d9)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828922d9-ffffffff828922fb: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acffb)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828acffb-ffffffff828ad01d: e820__range_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ad019)
Location: arch/x86/kernel/e820.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828ad019-ffffffff828ad03b: e820__range_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
