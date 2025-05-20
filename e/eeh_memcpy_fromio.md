# Function: <code>eeh_memcpy_fromio</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6b80)
Location: arch/powerpc/include/asm/eeh.h:439
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In fs/libfs.c (c0000000004bf99c)
Location: arch/powerpc/include/asm/eeh.h:439
Inline: True
Inline callers:
  - fs/libfs.c:memory_read_from_io_buffer
```
```
In drivers/pci/pci-sysfs.c (c000000000869b64)
Location: arch/powerpc/include/asm/eeh.h:439
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a49b8)
Location: arch/powerpc/include/asm/eeh.h:439
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/misc/sram.c (c0000000009ca1c0)
Location: arch/powerpc/include/asm/eeh.h:439
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
