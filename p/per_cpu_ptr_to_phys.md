# Function: <code>per_cpu_ptr_to_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b1d30)
Location: mm/percpu.c:1322
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff811b1d30-ffffffff811b1e48: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811caf40)
Location: mm/percpu.c:1335
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff811caf40-ffffffff811cb059: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811db070)
Location: mm/percpu.c:1339
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff811db070-ffffffff811db188: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e4a50)
Location: mm/percpu.c:1353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/crash.c:crash_load_segments
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff811e4a50-ffffffff811e4b82: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fad00)
Location: mm/percpu.c:1799
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff811fad00-ffffffff811fae19: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121bfc0)
Location: mm/percpu.c:1809
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff8121bfc0-ffffffff8121c0bd: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122efa0)
Location: mm/percpu.c:1820
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff8122efa0-ffffffff8122f09d: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123efa0)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff8123efa0-ffffffff8123f0a0: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124d400)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff8124d400-ffffffff8124d500: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8127b7a0)
Location: mm/percpu.c:2038
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:map_irq_stack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff8127b7a0-ffffffff8127b88d: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812862d0)
Location: mm/percpu.c:2191
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:map_irq_stack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff812862d0-ffffffff812863bd: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128b580)
Location: mm/percpu.c:2192
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff8128b580-ffffffff8128b67d: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812cb310)
Location: mm/percpu.c:2379
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff812cb310-ffffffff812cb437: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81328d20)
Location: mm/percpu.c:2377
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff81328d20-ffffffff81328e68: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139df20)
Location: mm/percpu.c:2369
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff8139df20-ffffffff8139e06e: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813d1080)
Location: mm/percpu.c:2369
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff813d1080-ffffffff813d11ce: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fbab0)
Location: mm/percpu.c:2398
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - kernel/crash_core.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:crash_notes_show
```
**Symbols:**

```
ffffffff813fbab0-ffffffff813fbbfe: per_cpu_ptr_to_phys (STB_GLOBAL)
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
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e3d48)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffff8000102e3d48-ffff8000102e3ed8: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0508010)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
c0508010-c050814c: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a43b0)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
c0000000003a43b0-c0000000003a4590: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001fa630)
Location: mm/percpu.c:2061
Inline: False
```
**Symbols:**

```
ffffffe0001fa630-ffffffe0001fa728: per_cpu_ptr_to_phys (STB_GLOBAL)
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
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81245a50)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff81245a50-ffffffff81245b50: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81238a00)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff81238a00-ffffffff81238b00: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812437f0)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff812437f0-ffffffff812438f0: per_cpu_ptr_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t per_cpu_ptr_to_phys(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81252fb0)
Location: mm/percpu.c:2061
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
  - arch/x86/mm/pti.c:pti_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - drivers/base/cpu.c:show_crash_notes
```
**Symbols:**

```
ffffffff81252fb0-ffffffff812530b0: per_cpu_ptr_to_phys (STB_GLOBAL)
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
