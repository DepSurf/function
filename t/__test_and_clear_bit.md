# Function: <code>__test_and_clear_bit</code>

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
In arch/x86/events/core.c (ffffffff81005a2a)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c3ab)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012698)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016b64)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/kgdb.c (ffffffff81061197)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063ab4)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
```
```
In mm/mmap.c (ffffffff811c8274)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81293f12)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff812cfe05)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpiolib.c (ffffffff81426845)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
```
```
In drivers/input/input.c (ffffffff81669a58)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81812901)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff810073eb)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c5eb)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012099)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015ddf)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/kgdb.c (ffffffff81060fd7)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810636d4)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
```
```
In kernel/time/timer.c (ffffffff810f4038)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
```
```
In mm/mmap.c (ffffffff811e43b4)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812c14c1)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff812ff9d7)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpiolib.c (ffffffff81472336)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/input/input.c (ffffffff816c9cff)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff818857f3)
Location: arch/x86/include/asm/bitops.h:271
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff810073eb)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c6c6)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810121c9)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015fb2)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/kgdb.c (ffffffff81064077)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066b8f)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In kernel/time/timer.c (ffffffff810fb1d8)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In mm/mmap.c (ffffffff811f43f8)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812d6aea)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81315a47)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpiolib.c (ffffffff81494456)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/input/input.c (ffffffff816f7cdf)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff818ba063)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff81007101)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c424)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81010862)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014462)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/kgdb.c (ffffffff81062fb7)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81065bcf)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_apic_eoi_write
```
```
In kernel/time/timer.c (ffffffff810fd759)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In mm/mmap.c (ffffffff811ff378)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812f4dcc)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8130cdc0)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff8170d77b)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff818e0a63)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff81007534)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100c9c7)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81010e62)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014cc2)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/kgdb.c (ffffffff81067141)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81069dc3)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_apic_eoi_write
```
```
In kernel/time/timer.c (ffffffff81107e86)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff81217978)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81319548)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81331a20)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff8177e9c1)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81966783)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff81007b5b)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d125)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810118b7)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101583b)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff81039901)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculative_store_bypass_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81069d3e)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106ca83)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
```
```
In kernel/time/timer.c (ffffffff81114a1c)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff81238d13)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81347356)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81360040)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff817bf9e2)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff819c00de)
Location: arch/x86/include/asm/bitops.h:287
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/core.c (ffffffff81007a3b)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d46d)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81011f37)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015f5b)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103ad6b)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106face)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81072b93)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111f1bc)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff8124c6d3)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8135f506)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81378380)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff817e6e92)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff819f721e)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a18307)
Location: arch/x86/include/asm/bitops.h:285
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100dd05)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810132ac)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101756a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103d2b5)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073d67)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107645f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112969d)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In mm/mmap.c (ffffffff8125eb03)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813886a2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a19a3)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815549f0)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff818278c8)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a66731)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a87df2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100e345)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a5c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f1a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103da75)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81074d27)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107746f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff81135640)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In mm/mmap.c (ffffffff8126d314)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813a105a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813ba813)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8157609c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff81858e2c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a9d251)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81abf092)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100f405)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101508c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019aba)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f836)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81040bd7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bd77)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e7bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
```
```
In kernel/time/timer.c (ffffffff81145520)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
```
```
In mm/mmap.c (ffffffff8129d514)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ed2d3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8140658b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In lib/xarray.c (ffffffff815fa7bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8161ab68)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8192a80c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81b98a41)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:83
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/intel/core.c (ffffffff8100e9f5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101552c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a12a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810202d6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81040b6b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bc67)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e3ef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In kernel/time/timer.c (ffffffff8114161a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In mm/mmap.c (ffffffff812a8925)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ff4ac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81415a49)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff8161efbd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81641218)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff81931a1c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81ba8711)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/intel/core.c (ffffffff8100edc3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810167bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b4ca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81022640)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81042560)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107ce17)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f4ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In kernel/time/timer.c (ffffffff81142e2c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In mm/mmap.c (ffffffff812addd2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81405842)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8141bc09)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff81602066)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In drivers/input/input.c (ffffffff81914d8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81a81a00)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81b97a73)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/intel/core.c (ffffffff8100f903)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101828a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101de6c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810264a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff810488ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108b347)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e27f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In kernel/time/timer.c (ffffffff811663bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In mm/mmap.c (ffffffff812ef548)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8145808d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8146efd8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff81670734)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In drivers/input/input.c (ffffffff819b6f1c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81b3b6d3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81c64519)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
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
In arch/x86/events/intel/core.c (ffffffff81010ec0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a3d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102091d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a5a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81051b80)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109b287)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ec4f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In kernel/time/timer.c (ffffffff8119901a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff813529f9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814d5cf0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff814f1ecb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In lib/xarray.c (ffffffff8178b5a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
```
```
In drivers/input/input.c (ffffffff81b16c79)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81cc76d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81e06cfe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff81e231cc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:107
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019e7c0)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
```
```
In mm/mmap.c (ffff8000103043c8)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffff80001047486c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffff800010490fc4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc670)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6fdc)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffff800010a98ee0)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffff800010d6dcc4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffff800010d9a23c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In kernel/time/timer.c (c03e83f4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (c0522b38)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (c0635d8c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (c0652140)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (c086764c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/gpio/gpio-xilinx.c (c0873b90)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (c0b7ac08)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (c0e6b43c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (c0e97014)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In kernel/time/timer.c (c0000000001fe8a4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (c0000000003d11e4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (c000000000595ed0)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (c0000000005b8b14)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (c000000000848314)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084da34)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (c000000000b77f50)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (c000000000eabbe0)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (c000000000ee07a0)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In kernel/time/timer.c (ffffffe00012c55c)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffe000210c08)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffe000300286)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffe000315daa)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad794)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/input/input.c (ffffffe0006a9bc4)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffe00089faca)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffe0008c1bfc)
Location: include/asm-generic/bitops/non-atomic.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100e345)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a5c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f1a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103dbf5)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073d27)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107646f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112ddf0)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In mm/mmap.c (ffffffff81265964)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8139963a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b2df3)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a13b)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8156aeac)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8180de3c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a3c5e1)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a5dee2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100cfa5)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81012c47)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101734a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8102d40e)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81063d77)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810663df)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112069f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff81257d84)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8138a0ca)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a3883)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8155b5ac)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff817d558c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff819f91fb)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a1afb2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100e305)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a1c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017eda)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103da35)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073cd7)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107641f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112bb10)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In mm/mmap.c (ffffffff81263704)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81396e9a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b0653)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff8184cfbc)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81aa8491)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81aca2d2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
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
In arch/x86/events/intel/core.c (ffffffff8100e4d5)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013c3c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101811a)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103eb4c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81075d37)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107846f)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
```
```
In kernel/time/timer.c (ffffffff811381ff)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff812730c4)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ab1ba)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c5123)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815842ec)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8186817c)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81ab452e)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81ad68a2)
Location: include/asm-generic/bitops-instrumented.h:197
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
