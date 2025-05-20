# Function: <code>bitmap_find_next_zero_area_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9520)
Location: lib/bitmap.c:307
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_first_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
**Symbols:**

```
ffffffff813f9520-ffffffff813f95b3: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440560)
Location: lib/bitmap.c:309
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81440560-ffffffff814405e6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d660)
Location: lib/bitmap.c:309
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8145d660-ffffffff8145d6e6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462950)
Location: lib/bitmap.c:309
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81462950-ffffffff814629d6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e840)
Location: lib/bitmap.c:311
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8148e840-ffffffff8148e8c6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3360)
Location: lib/bitmap.c:308
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff814c3360-ffffffff814c33e6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7df0)
Location: lib/bitmap.c:305
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff814d7df0-ffffffff814d7e76: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815039b0)
Location: lib/bitmap.c:305
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815039b0-ffffffff81503a36: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521950)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81521950-ffffffff815219d6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584a80)
Location: lib/bitmap.c:404
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81584a80-ffffffff81584b09: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1b80)
Location: lib/bitmap.c:404
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815a1b80-ffffffff815a1c09: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8ce0)
Location: lib/bitmap.c:406
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815a8ce0-ffffffff815a8d80: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611f80)
Location: lib/bitmap.c:406
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81611f80-ffffffff81612020: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de2c0)
Location: lib/bitmap.c:406
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff816de2c0-ffffffff816de375: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce480)
Location: lib/bitmap.c:417
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff817ce480-ffffffff817ce51e: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c930)
Location: lib/bitmap.c:417
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8180c930-ffffffff8180c9ce: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852b60)
Location: lib/bitmap.c:406
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81852b60-ffffffff81852bfe: bitmap_find_next_zero_area_off (STB_GLOBAL)
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
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b038)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffff80001062b038-ffff80001062b0ec: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2120)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
c07d2120-c07d21a0: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd5c0)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
c0000000007cd5c0-c0000000007cd6c8: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b98c)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffe00045b98c-ffffffe00045ba10: bitmap_find_next_zero_area_off (STB_GLOBAL)
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
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519f30)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81519f30-ffffffff81519fb6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a220)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff8150a220-ffffffff8150a2a6: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515fc0)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81515fc0-ffffffff81516046: bitmap_find_next_zero_area_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int bitmap_find_next_zero_area_off(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int align_mask, long unsigned int align_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f750)
Location: lib/bitmap.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/cma.c:cma_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8152f750-ffffffff8152f7d6: bitmap_find_next_zero_area_off (STB_GLOBAL)
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
