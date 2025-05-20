# Function: <code>zone_movable_is_highmem</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In arch/arm/mm/flush.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In arch/arm/mm/highmem.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In kernel/iomem.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/highmem.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
```
In lib/show_mem.c (0)
Location: include/linux/mmzone.h:905
Inline: True
```
</details>
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
