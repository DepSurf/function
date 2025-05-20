# Function: <code>paddr_vmcoreinfo_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110da70)
Location: kernel/kexec_core.c:1351
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffff8110da70-ffffffff8110daa1: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81115510)
Location: kernel/kexec_core.c:1398
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffff81115510-ffffffff81115542: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111cc30)
Location: kernel/kexec_core.c:1400
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffff8111cc30-ffffffff8111cc62: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024990)
Location: arch/x86/xen/mmu_pv.c:2693
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffff81024990-ffffffff81024a7b: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025530)
Location: arch/x86/xen/mmu_pv.c:2634
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffff81025530-ffffffff8102561b: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026280)
Location: arch/x86/xen/mmu_pv.c:2670
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff81026280-ffffffff8102635c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025e30)
Location: arch/x86/xen/mmu_pv.c:2810
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff81025e30-ffffffff81025f0c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027b30)
Location: arch/x86/xen/mmu_pv.c:2797
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff81027b30-ffffffff81027c0c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028470)
Location: arch/x86/xen/mmu_pv.c:2795
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff81028470-ffffffff8102854c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a380)
Location: arch/x86/xen/mmu_pv.c:2795
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff8102a380-ffffffff8102a462: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102ad60)
Location: arch/x86/xen/mmu_pv.c:2477
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff8102ad60-ffffffff8102ae42: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102b950)
Location: arch/x86/xen/mmu_pv.c:2476
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff8102b950-ffffffff8102ba44: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810300b0)
Location: arch/x86/xen/mmu_pv.c:2479
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff810300b0-ffffffff810301a4: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810356f0)
Location: arch/x86/xen/mmu_pv.c:2505
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff810356f0-ffffffff810357fb: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103d360)
Location: arch/x86/xen/mmu_pv.c:2505
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff8103d360-ffffffff8103d46b: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103d230)
Location: arch/x86/xen/mmu_pv.c:2513
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff8103d230-ffffffff8103d33b: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810436f0)
Location: arch/x86/xen/mmu_pv.c:2524
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/crash_core.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff810436f0-ffffffff810437fb: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff8000101c83b8)
Location: kernel/crash_core.c:373
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffff8000101c83b8-ffff8000101c8414: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c040f370)
Location: kernel/crash_core.c:373
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
c040f370-c040f398: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c000000000230a00)
Location: kernel/crash_core.c:373
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:register_fadump
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
c000000000230a00-c000000000230a20: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe000148284)
Location: kernel/crash_core.c:373
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
```
**Symbols:**

```
ffffffe000148284-ffffffe0001482b0: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810285d0)
Location: arch/x86/xen/mmu_pv.c:2795
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff810285d0-ffffffff810286ac: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811446f0)
Location: kernel/crash_core.c:373
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff811446f0-ffffffff81144723: paddr_vmcoreinfo_note (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028430)
Location: arch/x86/xen/mmu_pv.c:2795
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff81028430-ffffffff8102850c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t paddr_vmcoreinfo_note();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810290c0)
Location: arch/x86/xen/mmu_pv.c:2795
Inline: False
Direct callers:
  - kernel/ksysfs.c:vmcoreinfo_show
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
**Symbols:**

```
ffffffff810290c0-ffffffff8102919c: paddr_vmcoreinfo_note (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>phys_addr_t</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
