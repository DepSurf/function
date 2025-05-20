# Function: <code>arch___test_and_clear_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dd05)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810132ac)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101756a)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103d2b5)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073d67)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107645f)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112969d)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
```
```
In mm/mmap.c (ffffffff8125eb03)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813886a2)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a19a3)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815549f0)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff818278c8)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a66731)
Location: arch/x86/include/asm/bitops.h:175
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a87df2)
Location: arch/x86/include/asm/bitops.h:175
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a5c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f1a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103da75)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81074d27)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107746f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff81135640)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff8126d314)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813a105a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813ba813)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8157609c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff81858e2c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a9d251)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81abf092)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101508c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019aba)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f836)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81040bd7)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bd77)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e7bf)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff81145520)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff8129d514)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ed2d3)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8140658b)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In lib/xarray.c (ffffffff815fa7bd)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8161ab68)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8192a80c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81b98a41)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101552c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a12a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810202d6)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81040b6b)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bc67)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e3ef)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff8114161a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff812a8925)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ff4ac)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff81415a49)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff8161efbd)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81641218)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff81931a1c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81ba8711)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810167bf)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b4ca)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81022640)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81042560)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107ce17)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f4ff)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff81142e2c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff812addd2)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81405842)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8141bc09)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff81602066)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In drivers/input/input.c (ffffffff81914d8c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81a81a00)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81b97a73)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101828a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101de6c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810264a0)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff810488ad)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108b347)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e27f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff811663bc)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff812ef548)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8145808d)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8146efd8)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
```
```
In lib/xarray.c (ffffffff81670734)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In drivers/input/input.c (ffffffff819b6f1c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81b3b6d3)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81c64519)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a3d5)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102091d)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a5a7)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81051b80)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109b287)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ec4f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff8119901a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff813529f9)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814d5cf0)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff814f1ecb)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In lib/xarray.c (ffffffff8178b5a6)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In drivers/input/input.c (ffffffff81b16c79)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81cc76d5)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81e06cfe)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff81e231cc)
Location: arch/x86/include/asm/bitops.h:174
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015380)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e4e8)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102528d)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031197)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff8105f1bb)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b1e87)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810b62ff)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d757a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff813ccad2)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8156ea9d)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8158cac7)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81ca8114)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81e86d45)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81fdc0ce)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff81ff9f4f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff82048ff2)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff81014be3)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e1e1)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102517d)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810311cd)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff810608bb)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b4fa4)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810b93ff)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff811eb8da)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff814013a2)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815a685a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff815c3553)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81d0f624)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81ee33d9)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/rfkill/input.c (ffffffff82057dae)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff8207665e)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff820c784f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff81019bd3)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810242b1)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b2dd)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810374c2)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81067967)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bc3e4)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810c083f)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_apic_eoi_write
```
```
In kernel/time/timer.c (ffffffff81201a2a)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff8142d9f2)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815df6da)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff815feeb1)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81dc5224)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81fa71b9)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/rfkill/input.c (ffffffff8212a8ae)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff8214afde)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff821a21cf)
Location: arch/x86/include/asm/bitops.h:173
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e345)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a5c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f1a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103dbf5)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073d27)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107646f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112ddf0)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff81265964)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8139963a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b2df3)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a13b)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8156aeac)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8180de3c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81a3c5e1)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a5dee2)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81012c47)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101734a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8102d40e)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81063d77)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810663df)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112069f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff81257d84)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8138a0ca)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a3883)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8155b5ac)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff817d558c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff819f91fb)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81a1afb2)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a1c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017eda)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103da35)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073cd7)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107641f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112bb10)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In mm/mmap.c (ffffffff81263704)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81396e9a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b0653)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff8184cfbc)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81aa8491)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81aca2d2)
Location: arch/x86/include/asm/bitops.h:174
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
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff81013c3c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101811a)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/kernel/process.c (ffffffff8103eb4c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff81075d37)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107846f)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
```
```
In kernel/time/timer.c (ffffffff811381ff)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In mm/mmap.c (ffffffff812730c4)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ab1ba)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c5123)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815842ec)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
```
```
In drivers/input/input.c (ffffffff8186817c)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/rfkill/input.c (ffffffff81ab452e)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/xarray.c (ffffffff81ad68a2)
Location: arch/x86/include/asm/bitops.h:174
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
