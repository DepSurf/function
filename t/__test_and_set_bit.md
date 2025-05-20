# Function: <code>__test_and_set_bit</code>

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
In arch/x86/events/core.c (ffffffff81004fae)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In kernel/sysctl_binary.c (ffffffff81089cee)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In mm/mmap.c (ffffffff811c841b)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812947c8)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813ae5c5)
Location: arch/x86/include/asm/bitops.h:231
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
In drivers/xen/xen-acpi-processor.c (ffffffff814d63d7)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81719451)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff810051ea)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In kernel/sysctl_binary.c (ffffffff8108cc40)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In mm/mmap.c (ffffffff811e45d6)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812c1dc3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813f2285)
Location: arch/x86/include/asm/bitops.h:231
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
In drivers/xen/xen-acpi-processor.c (ffffffff81527175)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81781940)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff8100520a)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In kernel/sysctl_binary.c (ffffffff81091bc0)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In mm/mmap.c (ffffffff811f45f4)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812d7425)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8140baf5)
Location: arch/x86/include/asm/bitops.h:244
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
In drivers/xen/xen-acpi-processor.c (ffffffff815536c5)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff817af250)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff81005080)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In kernel/sysctl_binary.c (ffffffff8108ed5f)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
```
```
In mm/mmap.c (ffffffff811ff55b)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff812f57b9)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814196e5)
Location: arch/x86/include/asm/bitops.h:244
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
In drivers/xen/xen-acpi-processor.c (ffffffff81568025)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff817cdb60)
Location: arch/x86/include/asm/bitops.h:244
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff81005330)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81042165)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff81095c1f)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
```
```
In mm/mmap.c (ffffffff81217b3d)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81319f1c)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8144421b)
Location: arch/x86/include/asm/bitops.h:245
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
In drivers/xen/xen-acpi-processor.c (ffffffff815cc1e5)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81847660)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff81005ae3)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/kernel/process.c (ffffffff81039810)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculative_store_bypass_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81044045)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff81098df6)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
```
```
In mm/mmap.c (ffffffff81238ea0)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81347a0a)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8138710d)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814770eb)
Location: arch/x86/include/asm/bitops.h:246
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
In drivers/xen/xen-acpi-processor.c (ffffffff81604a26)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81891f20)
Location: arch/x86/include/asm/bitops.h:246
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In arch/x86/events/core.c (ffffffff810059e3)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/kernel/process.c (ffffffff8103ab6c)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81045a45)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a1176)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
```
```
In mm/mmap.c (ffffffff8124c860)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8135fbba)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8139fc1d)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81407808)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814952c5)
Location: arch/x86/include/asm/bitops.h:245
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
In drivers/xen/xen-acpi-processor.c (ffffffff8161fb06)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff818b2880)
Location: arch/x86/include/asm/bitops.h:245
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a182d5)
Location: arch/x86/include/asm/bitops.h:245
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
In arch/x86/events/core.c (ffffffff81006023)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/kernel/process.c (ffffffff8103d1bf)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104826a)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a5bc2)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff8125eca2)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81388d31)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813c9f0d)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814349c1)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c2caf)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff818ff011)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a87dc1)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048b1a)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810ac1a2)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff8126d4b2)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813a16a4)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813e3213)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8144e741)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814dbadf)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81931381)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81abf061)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cc36)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810b3e62)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
```
```
In mm/mmap.c (ffffffff8129d6b2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ed8ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814307b3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814a072a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8153b3af)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
Inline callers:
  - lib/xarray.c:xas_expand
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8172612a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
Inline: True
```
```
In net/core/dev.c (ffffffff81a06b2a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:69
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c096)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812a8b27)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813fffef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144955c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814be0fa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815581bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_expand
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81c06287)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81763dc0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81a080fa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dbd6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812adfd4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814063a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144eecc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff814c3fa2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81560aef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf7f19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81747700)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff819ee7f4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810553a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff812ef7b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81458c08)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814a2a1b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8151c972)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815c1ebf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf7051)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c8740)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81a9faac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810612de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In mm/mmap.c (ffffffff81352bff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff814d67b7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff81529e50)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff815afb31)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8166c39f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebf130)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81905a60)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_kdskbsent
```
```
In net/core/dev.c (ffffffff81c17ddf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:93
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
In arch/arm64/mm/context.c (ffff8000100afd94)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/sysctl_binary.c (ffff800010105004)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In mm/mmap.c (ffff800010304594)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffff800010474e88)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffff8000104bc77c)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffff800010538c8c)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffff8000105d804c)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In net/core/dev.c (ffff800010bcfb24)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffff800010d9a1ec)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In arch/arm/mm/context.c (c03225c8)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/sysctl_binary.c (c0360b3c)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In mm/mmap.c (c0522d18)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (c06364b8)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (c067fdec)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (c06ef754)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (c07855f0)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In net/core/dev.c (c0ce4298)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (c0e96fcc)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In kernel/sysctl_binary.c (c00000000014cb48)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In mm/mmap.c (c0000000003d1424)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (c000000000596718)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (c0000000005f2524)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (c000000000687bf4)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (c000000000767640)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In net/core/dev.c (c000000000cac720)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (c000000000ee0640)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In kernel/sysctl_binary.c (ffffffe0000cacf4)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In mm/mmap.c (ffffffe000210d5a)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffe000300aca)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffe0003384be)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffe0003978de)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffe00041bd2e)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In net/core/dev.c (ffffffe000759cfc)
Location: include/asm-generic/bitops/non-atomic.h:58
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffe0008c1b7a)
Location: include/asm-generic/bitops/non-atomic.h:58
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
In arch/x86/kernel/process.c (ffffffff8103daff)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c8a)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a62b5)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff81265b02)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff81399c84)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813db7f3)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81446d21)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d40bf)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff818d1381)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a5deb1)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8103801a)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff81094c95)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff81257f22)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff8138a714)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813cc273)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81437771)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c4adf)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81a1af81)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048aca)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810a5a72)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff812638a2)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813974e4)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813d8c93)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff81442dc1)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d014f)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81922381)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81aca2a1)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049eda)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In kernel/sysctl_binary.c (ffffffff810adb32)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff81273262)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In fs/ext4/ialloc.c (ffffffff813ab867)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813edf73)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In security/keys/keyctl_pkey.c (ffffffff8145a0f1)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814e8c1f)
Location: include/asm-generic/bitops-instrumented.h:155
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
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:upload_pm_data
```
```
In net/core/dev.c (ffffffff81943468)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In lib/xarray.c (ffffffff81ad6871)
Location: include/asm-generic/bitops-instrumented.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
