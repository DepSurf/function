# Function: <code>alloc_pages_exact</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194f30)
Location: mm/page_alloc.c:3481
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81194f30-ffffffff81194fa4: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a90a0)
Location: mm/page_alloc.c:3900
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff811a90a0-ffffffff811a910e: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9630)
Location: mm/page_alloc.c:4056
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff811b9630-ffffffff811b966f: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c16a0)
Location: mm/page_alloc.c:4343
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff811c16a0-ffffffff811c16df: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5ac0)
Location: mm/page_alloc.c:4462
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff811d5ac0-ffffffff811d5aff: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6ed0)
Location: mm/page_alloc.c:4594
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff811f6ed0-ffffffff811f6f0f: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209270)
Location: mm/page_alloc.c:4765
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff81209270-ffffffff812092af: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270690)
Location: mm/page_alloc.c:4934
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff81270690-ffffffff812706e5: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f4d0)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff8127f4d0-ffffffff8127f525: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1bf0)
Location: mm/page_alloc.c:5055
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff812b1bf0-ffffffff812b1c5e: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd560)
Location: mm/page_alloc.c:5234
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff812bd560-ffffffff812bd5d7: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c24f0)
Location: mm/page_alloc.c:5437
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff812c24f0-ffffffff812c2568: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305ec0)
Location: mm/page_alloc.c:5618
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff81305ec0-ffffffff81305f38: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136df20)
Location: mm/page_alloc.c:5673
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
**Symbols:**

```
ffffffff8136df20-ffffffff8136dfb5: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6820)
Location: mm/page_alloc.c:5816
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
**Symbols:**

```
ffffffff813e6820-ffffffff813e68b5: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141b7c0)
Location: mm/page_alloc.c:4744
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/mm_init.c:alloc_large_system_hash
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
**Symbols:**

```
ffffffff8141b7c0-ffffffff8141b851: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81448800)
Location: mm/page_alloc.c:4833
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/mm_init.c:alloc_large_system_hash
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
**Symbols:**

```
ffffffff81448800-ffffffff81448891: alloc_pages_exact (STB_GLOBAL)
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
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317098)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - virt/kvm/arm/mmu.c:kvm_alloc_stage2_pgd
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffff800010317098-ffff800010317148: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05339dc)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/virtio/virtio_ring.c:vring_alloc_queue
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/memalloc.c:snd_dma_alloc_pages
```
**Symbols:**

```
c05339dc-c0533a68: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9400)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/virtio/virtio_ring.c:vring_alloc_queue
```
**Symbols:**

```
c0000000003e9400-c0000000003e94a0: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ed02)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/virtio/virtio_ring.c:vring_alloc_queue
```
**Symbols:**

```
ffffffe00021ed02-ffffffe00021edb4: alloc_pages_exact (STB_GLOBAL)
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
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277b20)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff81277b20-ffffffff81277b75: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269a30)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/virtio/virtio_ring.c:vring_alloc_queue
```
**Symbols:**

```
ffffffff81269a30-ffffffff81269a85: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812758c0)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff812758c0-ffffffff81275915: alloc_pages_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *alloc_pages_exact(size_t size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285480)
Location: mm/page_alloc.c:4952
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff81285480-ffffffff812854d5: alloc_pages_exact (STB_GLOBAL)
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
