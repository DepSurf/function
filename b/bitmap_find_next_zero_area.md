# Function: <code>bitmap_find_next_zero_area</code>

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
In kernel/irq/irqdesc.c (ffffffff81818e56)
Location: include/linux/bitmap.h:137
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffffffff81407271)
Location: include/linux/bitmap.h:137
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/iommu-helper.c (ffffffff814131ad)
Location: include/linux/bitmap.h:137
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8142cf69)
Location: include/linux/bitmap.h:137
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
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
In kernel/irq/irqdesc.c (ffffffff81892aa9)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffffffff8144f0d2)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff8145aeca)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff81478181)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d38b)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff818c73a9)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffffffff8146dad2)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff814799ba)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff814994e1)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb45b)
Location: include/linux/bitmap.h:139
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff818feaf9)
Location: include/linux/bitmap.h:138
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffffffff81473213)
Location: include/linux/bitmap.h:138
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81482d17)
Location: include/linux/bitmap.h:138
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff814a30ff)
Location: include/linux/bitmap.h:138
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf6da)
Location: include/linux/bitmap.h:138
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81988d35)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff810f8f8c)
Location: include/linux/bitmap.h:148
Inline: True
```
```
In mm/percpu.c (ffffffff811fa021)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/genalloc.c (ffffffff814a05a3)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff814bed57)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff814e1e6f)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173bd2a)
Location: include/linux/bitmap.h:148
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff819e567a)
Location: include/linux/bitmap.h:157
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811014ec)
Location: include/linux/bitmap.h:157
Inline: True
```
```
In mm/percpu.c (ffffffff8121a1a3)
Location: include/linux/bitmap.h:157
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/genalloc.c (ffffffff814d5733)
Location: include/linux/bitmap.h:157
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit_align
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff814eff26)
Location: include/linux/bitmap.h:157
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff81511680)
Location: include/linux/bitmap.h:157
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c587)
Location: include/linux/bitmap.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81a2088a)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8110ce06)
Location: include/linux/bitmap.h:165
Inline: True
```
```
In mm/percpu.c (ffffffff8122d0b5)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/genalloc.c (ffffffff814ea203)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81503e46)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff81526d30)
Location: include/linux/bitmap.h:165
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2ae7)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81a90dba)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811164e9)
Location: include/linux/bitmap.h:165
Inline: True
```
```
In lib/genalloc.c (ffffffff81516f14)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81531fc9)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff81555c68)
Location: include/linux/bitmap.h:165
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1c0a)
Location: include/linux/bitmap.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81ac80fa)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811228b9)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In lib/genalloc.c (ffffffff815379b4)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81552e09)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff815772a8)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812ada)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81bc0c29)
Location: include/linux/bitmap.h:185
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112ef09)
Location: include/linux/bitmap.h:185
Inline: True
```
```
In lib/genalloc.c (ffffffff8159bb04)
Location: include/linux/bitmap.h:185
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff815dc1e9)
Location: include/linux/bitmap.h:185
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8161ba19)
Location: include/linux/bitmap.h:185
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e3e7a)
Location: include/linux/bitmap.h:185
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81c39cb9)
Location: include/linux/bitmap.h:183
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112aee9)
Location: include/linux/bitmap.h:183
Inline: True
```
```
In lib/genalloc.c (ffffffff815b7524)
Location: include/linux/bitmap.h:183
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff815f9e89)
Location: include/linux/bitmap.h:183
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8164210a)
Location: include/linux/bitmap.h:183
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ed35a)
Location: include/linux/bitmap.h:183
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81c2c289)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112b183)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In lib/genalloc.c (ffffffff815c248c)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff815dca69)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8162506d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0b2a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81d4a979)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8114bb63)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In lib/genalloc.c (ffffffff8162a3bc)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff816483c9)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8169487d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196b03a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81f1a01e)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff81171503)
Location: include/linux/bitmap.h:190
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126e9b7)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In lib/genalloc.c (ffffffff816fb6ff)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff8175e796)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff817b53da)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5397)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff820c1c4e)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811a7b23)
Location: include/linux/bitmap.h:193
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c417f)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In lib/genalloc.c (ffffffff817ee343)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff8188bfb6)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff818cf6de)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f427)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/matrix.c (ffffffff811b9803)
Location: include/linux/bitmap.h:193
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812eb12f)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In lib/genalloc.c (ffffffff8182e743)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff818ce426)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8191269e)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb69c7)
Location: include/linux/bitmap.h:193
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/matrix.c (ffffffff811c96c3)
Location: include/linux/bitmap.h:195
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81309652)
Location: include/linux/bitmap.h:195
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In lib/genalloc.c (ffffffff81880303)
Location: include/linux/bitmap.h:195
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff819201d6)
Location: include/linux/bitmap.h:195
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6b717)
Location: include/linux/bitmap.h:195
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010d9bf64)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffff800010643e68)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In drivers/pwm/core.c (ffff8000106d7fa8)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001071faf8)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107255a4)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010725e9c)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c8cc)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4bb2c)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c031def0)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
```
```
In kernel/irq/irqdesc.c (c0e985ec)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (c07ea5cc)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In drivers/irqchip/irq-alpine-msi.c (c08131dc)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ea70)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc
```
```
In drivers/pwm/core.c (c0875880)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1dda8)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7924)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d9274)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
```
```
In kernel/irq/irqdesc.c (c0000000001d1ecc)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (c0000000007f0254)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (c000000000811980)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (c0000000008503d4)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12a3c)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0008c41ee)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In lib/genalloc.c (ffffffe000470de4)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In drivers/pwm/core.c (ffffffe0004b1f92)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668a34)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
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
In kernel/irq/irqdesc.c (ffffffff81a66f6a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8111ae99)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In lib/genalloc.c (ffffffff8152ff94)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff8154b3e9)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8156c0b8)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817caeba)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81a23a2a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8110bf09)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In lib/genalloc.c (ffffffff81520274)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff8153b6c9)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/irq/irqdesc.c (ffffffff81ad337a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff81118d89)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In lib/genalloc.c (ffffffff8152bcd4)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81547129)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff8156aff8)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8180795a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In kernel/irq/irqdesc.c (ffffffff81adf87a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff81124419)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In lib/genalloc.c (ffffffff81545ad4)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_first_fit_order_align
  - lib/genalloc.c:gen_pool_fixed_alloc
  - lib/genalloc.c:gen_pool_first_fit
```
```
In lib/iommu-helper.c (ffffffff81560f79)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff815854f8)
Location: include/linux/bitmap.h:169
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821a6a)
Location: include/linux/bitmap.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
</details>
</li>
</ul>

## Differences
