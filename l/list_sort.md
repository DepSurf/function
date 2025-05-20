# Function: <code>list_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff813faa10)
Location: lib/list_sort.c:104
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff813faa10-ffffffff813fac69: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81441ad0)
Location: lib/list_sort.c:104
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81441ad0-ffffffff81441d42: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff8145ece0)
Location: lib/list_sort.c:104
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8145ece0-ffffffff8145ef52: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/list_sort.c (ffffffff81464030)
Location: lib/list_sort.c:101
Inline: True
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81464030-ffffffff81464287: list_sort.part.0 (STB_LOCAL)
ffffffff81464290-ffffffff814642a5: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/list_sort.c (ffffffff8148ffb0)
Location: lib/list_sort.c:102
Inline: True
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8148ffb0-ffffffff8149020b: list_sort.part.0 (STB_LOCAL)
ffffffff81490210-ffffffff81490225: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/list_sort.c (ffffffff814c4fd0)
Location: lib/list_sort.c:102
Inline: True
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814c4da0-ffffffff814c4fca: list_sort.part.0 (STB_LOCAL)
ffffffff814c4fe4-ffffffff814c5019: list_sort.part.0.cold.1 (STB_LOCAL)
ffffffff814c4fd0-ffffffff814c4fe4: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/list_sort.c (ffffffff814d96c0)
Location: lib/list_sort.c:102
Inline: True
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814d9490-ffffffff814d96ba: list_sort.part.0 (STB_LOCAL)
ffffffff814d96d4-ffffffff814d9709: list_sort.part.0.cold.1 (STB_LOCAL)
ffffffff814d96c0-ffffffff814d96d4: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff815051d0)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff815051d0-ffffffff81505468: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff815231b0)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff815231b0-ffffffff81523448: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81586700)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81586700-ffffffff81586998: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff815a39f0)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff815a39f0-ffffffff815a3c88: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff815aa910)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff815aa910-ffffffff815aaba8: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81613bc0)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81613bc0-ffffffff81613e58: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff816e0520)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff816e0520-ffffffff816e06ea: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff817d0850)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff817d0850-ffffffff817d0a1a: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff8180f4a0)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff8180f4a0-ffffffff8180f66a: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, list_cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81855120)
Location: lib/list_sort.c:185
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_sort_ioends
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/gpu/drm/drm_modes.c:drm_mode_sort
```
**Symbols:**

```
ffffffff81855120-ffffffff818552ea: list_sort (STB_GLOBAL)
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
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffff80001062cef8)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffff80001062cef8-ffff80001062d1f4: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (c07d3ab0)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
c07d3ab0-c07d3d64: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (c0000000007cfd70)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
c0000000007cfd70-c0000000007d019c: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffe00045ceba)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffe00045ceba-ffffffe00045d0a6: list_sort (STB_GLOBAL)
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
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff8151b790)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/nvme/host/core.c:nvme_scan_work
```
**Symbols:**

```
ffffffff8151b790-ffffffff8151ba28: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff8150ba80)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/nvme/host/core.c:nvme_scan_work
```
**Symbols:**

```
ffffffff8150ba80-ffffffff8150bd18: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81517820)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81517820-ffffffff81517ab8: list_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void list_sort(void *priv, struct list_head *head, int (*cmp)(void *, struct list_head *, struct list_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/list_sort.c (ffffffff81530fc0)
Location: lib/list_sort.c:188
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - block/blk-mq.c:blk_mq_flush_plug_list
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81530fc0-ffffffff81531258: list_sort (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*cmp)(void *, struct list_head *, struct list_head *)</code> ➡️ <code>list_cmp_func_t cmp</code>
</li>
</ul>
</details>
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
