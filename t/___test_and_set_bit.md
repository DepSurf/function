# Function: <code>___test_and_set_bit</code>

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
In arch/x86/kernel/process.c (ffffffff8105efa8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fc6e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff813ccd2f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8156f57b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff815c87b6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a351)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8172726f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a60240)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81dc8d0f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071877)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff81401691)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815a73c3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8160056c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81692c31)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81763664)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaa910)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81e37270)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079097)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff8142dce9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff815e0201)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff816392bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf201)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a5224)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afd3a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81ef5290)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:97
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
