# Function: <code>_find_next_zero_bit</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_next_zero_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d7090)
Location: lib/find_bit.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - io_uring/filetable.c:__io_fixed_fd_install
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff817d7090-ffffffff817d7113: _find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_next_zero_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81816160)
Location: lib/find_bit.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/vmalloc.c:vmap_ram_vread_iter
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - io_uring/filetable.c:__io_fixed_fd_install
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_find_bit
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81816160-ffffffff818161e0: _find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_next_zero_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185b2a0)
Location: lib/find_bit.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/vmalloc.c:vmap_ram_vread_iter
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - io_uring/filetable.c:__io_fixed_fd_install
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_find_bit
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8185b2a0-ffffffff8185b320: _find_next_zero_bit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
