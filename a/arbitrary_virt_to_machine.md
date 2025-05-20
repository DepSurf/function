# Function: <code>arbitrary_virt_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ea40)
Location: arch/x86/xen/mmu.c:134
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101ea40-ffffffff8101eb1c: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de70)
Location: arch/x86/xen/mmu.c:135
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101de70-ffffffff8101df6d: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e560)
Location: arch/x86/xen/mmu.c:135
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101e560-ffffffff8101e65d: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a3d0)
Location: arch/x86/xen/mmu.c:22
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101a3d0-ffffffff8101a4ed: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ac90)
Location: arch/x86/xen/mmu.c:22
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101ac90-ffffffff8101adbd: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b680)
Location: arch/x86/xen/mmu.c:22
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101b680-ffffffff8101b7c2: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b8f0)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101b8f0-ffffffff8101ba32: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d430)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101d430-ffffffff8101d577: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ddd0)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101ddd0-ffffffff8101df17: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020190)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81020190-ffffffff810202d7: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020bc0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff81020bc0-ffffffff81020d07: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022f60)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff81022f60-ffffffff810230a4: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810270d0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff810270d0-ffffffff81027214: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102b2a0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff8102b2a0-ffffffff8102b3d9: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81031fc0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff81031fc0-ffffffff810320f9: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81031fc0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff81031fc0-ffffffff810320f9: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810382b0)
Location: arch/x86/xen/mmu.c:18
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:map_ring_apply
```
**Symbols:**

```
ffffffff810382b0-ffffffff810383e9: arbitrary_virt_to_machine (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ddd0)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101ddd0-ffffffff8101df17: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101dd90)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101dd90-ffffffff8101ded7: arbitrary_virt_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101dfe0)
Location: arch/x86/xen/mmu.c:18
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_mfn
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8101dfe0-ffffffff8101e127: arbitrary_virt_to_machine (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
