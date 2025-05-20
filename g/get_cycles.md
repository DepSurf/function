# Function: <code>get_cycles</code>

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
In arch/x86/kernel/tsc.c (ffffffff810377d7)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In mm/slub.c (ffffffff811eaa61)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff812ce210)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In lib/random32.c (ffffffff81f9e498)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff815118b9)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/iommu/dmar.c (ffffffff815334c3)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535cdc)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c918)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff810373d2)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8120a006)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff812fd800)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff813efabd)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff81fc9961)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff81566485)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff81587a55)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158a45f)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81591599)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff81037162)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8121c076)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81313880)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8140933d)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff820068e4)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff81592be5)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815b5115)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b7acf)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bee59)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff810351fc)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81227ad9)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8130b15e)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81416a15)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff820e7940)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff815a6b3e)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815cafcd)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cdbaf)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4a48)
Location: arch/x86/include/asm/tsc.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103754c)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81243c16)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8132fbee)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814411fd)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff826f06ae)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff8160d43e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff81631d9d)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816349ef)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b7dd)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff810385ae)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81266355)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8135de1e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814740f5)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff8271ab17)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff816464bd)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8166d12d)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8166ff4f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676dc6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff810390ce)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8127b090)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81375d8e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81491c65)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828d2a3a)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff8166510d)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8168b53e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e46f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695e76)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103b662)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81296a29)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8139f26c)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814bf2c5)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828eca61)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828f9e31)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816c2f6e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c5adf)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce7b6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103be32)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097b03)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812a67e2)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813b80d7)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d8115)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f5bb2)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff82902d34)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816e5e5e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e8b0f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f25f6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103ebf1)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a861)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:check_enable
  - arch/x86/platform/uv/tlb_uv.c:disable_for_period
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812daf98)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81403ca7)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815378e5)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff82d09245)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff8177116c)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c73e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179faa6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7723)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aab3f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103eca1)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff812e7888)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81416eff)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815547a5)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff82ff67f6)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff8178c19c)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa40e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad646)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b35c3)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b709f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff81040715)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff812eeff8)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff8141db1f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8155cf15)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff832014de)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff817714ea)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d1ae)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8178ffd6)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817966f3)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a38f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff81046805)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81337308)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81471099)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815be245)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff832e8b21)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff817f709a)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel/dmar.c (ffffffff8181450e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81817846)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e683)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818229cf)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8104f0a0)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff813a8c08)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff814f276f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195535e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff819587ca)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ea53)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8196267f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8105c240)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81429cea)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff8158c53c)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb95e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf95a)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac64c3)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb3ff)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8105dd50)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8145f0ca)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff815c2677)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0823e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b12b8a)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b130a3)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17e0f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff81064e10)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8145a239)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff815fb2f7)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c25e)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b679ca)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d74f)
Location: arch/x86/include/asm/tsc.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000425ea4)
Location: arch/powerpc/include/asm/timex.h:18
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (c0000000005b61cc)
Location: arch/powerpc/include/asm/timex.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (c000000000761468)
Location: arch/powerpc/include/asm/timex.h:18
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (c0000000013a0150)
Location: arch/powerpc/include/asm/timex.h:18
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (c0000000013a83a4)
Location: arch/powerpc/include/asm/timex.h:18
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In init/calibrate.c (ffffffe0000b4cda)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
```
In fs/ext4/mballoc.c (ffffffe00031384a)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffe000418444)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffe00002a1e2)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffe00002f980)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:rand_initialize
```
```
In drivers/clocksource/timer-riscv.c (ffffffe00071e4c6)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - drivers/clocksource/timer-riscv.c:riscv_sched_clock
  - drivers/clocksource/timer-riscv.c:riscv_clocksource_rdtime
  - drivers/clocksource/timer-riscv.c:riscv_clock_next_event
```
```
In arch/riscv/lib/delay.c (ffffffe0008c3c5a)
Location: arch/riscv/include/asm/timex.h:13
Inline: True
Inline callers:
  - arch/riscv/lib/delay.c:ndelay
  - arch/riscv/lib/delay.c:ndelay
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
In arch/x86/kernel/tsc.c (ffffffff8103bf92)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8129edc2)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813b06b7)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d06f5)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828dea66)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828ea51b)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816ab93e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ae5ef)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7de6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8102b7e5)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff81290902)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813a1147)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814c1115)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828d7182)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828e19a8)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8168929e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168bf4f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695a26)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103bdf2)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In mm/slub.c (ffffffff8129cbd2)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813adf17)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814cc785)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f17da)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828fe057)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816d9b1e)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc7cf)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e62b6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
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
In arch/x86/kernel/tsc.c (ffffffff8103ce42)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098fc3)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812acc36)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813c3263)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814e5255)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f6c06)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff82903d96)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816f40ce)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6e0f)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff817009b6)
Location: arch/x86/include/asm/tsc.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
</details>
</li>
</ul>

## Differences
