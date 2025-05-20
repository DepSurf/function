# Function: <code>arch___test_and_set_bit</code>

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
In arch/x86/events/core.c (ffffffff81006023)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/kernel/process.c (ffffffff8103d1bf)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104826a)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a5bc2)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
```
```
In mm/mmap.c (ffffffff8125eca2)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81388d31)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813c9f0d)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814349c1)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c2caf)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816530d0)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff818ff011)
Location: arch/x86/include/asm/bitops.h:149
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a87dc1)
Location: arch/x86/include/asm/bitops.h:149
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
In arch/x86/kernel/process.c (ffffffff8103d97f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048b1a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810ac1a2)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff8126d4b2)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813a16a4)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813e3213)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8144e741)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814dbadf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81675678)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81931381)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81abf061)
Location: arch/x86/include/asm/bitops.h:148
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
In arch/x86/kernel/process.c (ffffffff810409ba)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cc36)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810b3e62)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff8129d6b2)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ed8ce)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814307b3)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814a072a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8153b3af)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In lib/xarray.c (ffffffff815fa78e)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8172612a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In net/core/dev.c (ffffffff81a06b2a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/kernel/process.c (ffffffff8104090a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c096)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812a8b27)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813fffef)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144955c)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814be0fa)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815581bf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In lib/xarray.c (ffffffff8161fa18)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_expand
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81c06287)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81763dc0)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81a080fa)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/kernel/process.c (ffffffff810422fd)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dbd6)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812adfd4)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814063a8)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144eecc)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814c3fa2)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81560aef)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In lib/xarray.c (ffffffff81603198)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf7f19)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81747700)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff819ee7f4)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/kernel/process.c (ffffffff8104864a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810553a6)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812ef7b1)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81458c08)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814a2a1b)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8151c972)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815c1ebf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In lib/xarray.c (ffffffff81671674)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf7051)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c8740)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81a9faac)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/kernel/process.c (ffffffff81051928)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810612de)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff81352bff)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814d67b7)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff81529e50)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff815afb31)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8166c39f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In lib/xarray.c (ffffffff8178c0e5)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebf130)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81905a60)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81c17ddf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
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
In arch/x86/kernel/process.c (ffffffff8105efa8)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fc6e)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff813ccd2f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8156f57b)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff815c87b6)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a351)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8172726f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a3300c)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a60240)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81dc8d0f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In lib/xarray.c (ffffffff8204869f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
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
In arch/x86/kernel/process.c (ffffffff810606a8)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071877)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff81401691)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815a73c3)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8160056c)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81692c31)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81763664)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7c8fc)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaa910)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81e37270)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In lib/xarray.c (ffffffff820c6eaf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
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
In arch/x86/kernel/process.c (ffffffff8106772f)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079097)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff8142dce9)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815e0201)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff816392bc)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf201)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a5224)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81acedac)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afd3a0)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81ef5290)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In lib/xarray.c (ffffffff821a182f)
Location: arch/x86/include/asm/bitops.h:147
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
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
In arch/x86/kernel/process.c (ffffffff8103daff)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c8a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a62b5)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff81265b02)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81399c84)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813db7f3)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81446d21)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d40bf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163b368)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff818d1381)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a5deb1)
Location: arch/x86/include/asm/bitops.h:148
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
In arch/x86/kernel/process.c (ffffffff8102d271)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8103801a)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff81094c95)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff81257f22)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8138a714)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813cc273)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81437771)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c4adf)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In net/core/dev.c (ffffffff8188b217)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a1af81)
Location: arch/x86/include/asm/bitops.h:148
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
In arch/x86/kernel/process.c (ffffffff8103d93f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048aca)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a5a72)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff812638a2)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813974e4)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813d8c93)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81442dc1)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d014f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816694b8)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81922381)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81aca2a1)
Location: arch/x86/include/asm/bitops.h:148
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
In arch/x86/kernel/process.c (ffffffff8103ea58)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049eda)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810adb32)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In mm/mmap.c (ffffffff81273262)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ab867)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813edf73)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8145a0f1)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814e8c1f)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683a78)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81943468)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81ad6871)
Location: arch/x86/include/asm/bitops.h:148
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
