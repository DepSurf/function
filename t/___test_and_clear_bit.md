# Function: <code>___test_and_clear_bit</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015380)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e4e8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102528d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031197)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff8105f1bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b1e87)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810b62ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d757a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff813ccad2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8156ea9d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff8158cac7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81ca8114)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81e86d45)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/rfkill/input.c (ffffffff81fdc0ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff81ff9f4f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff82048ff2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e1e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102517d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810311cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff810608bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b4fa4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810b93ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
```
```
In kernel/time/timer.c (ffffffff811eb8da)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff814013a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815a685a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff815c3553)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81d0f624)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81ee33d9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/rfkill/input.c (ffffffff82057dae)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff8207665e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff820c784f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/p4.c (ffffffff810242b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b2dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810374c2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/process.c (ffffffff81067967)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bc3e4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810c083f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_apic_eoi_write
```
```
In kernel/time/timer.c (ffffffff81201a2a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In mm/mmap.c (ffffffff8142d9f2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815df6da)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/mballoc.c (ffffffff815feeb1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In drivers/input/input.c (ffffffff81dc5224)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
```
```
In net/ethtool/fec.c (ffffffff81fa71b9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/rfkill/input.c (ffffffff8212a8ae)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/mptcp/protocol.c (ffffffff8214afde)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In lib/xarray.c (ffffffff821a21cf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:112
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
