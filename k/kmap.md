# Function: <code>kmap</code>

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
In kernel/kexec_core.c (ffffffff8110d1b7)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/shmem.c (ffffffff811aa43b)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_follow_link
```
```
In mm/memory.c (ffffffff811bba44)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff811d6420)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/userfaultfd.c (ffffffff81207cba)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81213031)
Location: include/linux/highmem.h:56
Inline: True
```
```
In fs/namei.c (ffffffff81217e9b)
Location: include/linux/highmem.h:56
Inline: True
```
```
In fs/splice.c (ffffffff8123db12)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff8125bc2c)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff812695f9)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8126c353)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/symlink.c (ffffffff812be6c4)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
```
```
In fs/ecryptfs/read_write.c (ffffffff81304965)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81305ca8)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
```
```
In fs/fuse/file.c (ffffffff81315903)
Location: include/linux/highmem.h:56
Inline: True
```
```
In crypto/ahash.c (ffffffff813a2a50)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff813fa4d5)
Location: include/linux/highmem.h:56
Inline: True
```
```
In lib/iov_iter.c (ffffffff813fcd31)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/acpi/osl.c (ffffffff8181ad7f)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8152656a)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/base/firmware_class.c (ffffffff8155e358)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_read
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In net/core/sock.c (ffffffff81700c3f)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff8170d992)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff8175ec65)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff81114a8e)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff811d6634)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff811f44f4)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/userfaultfd.c (ffffffff8122d60d)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8123a596)
Location: include/linux/highmem.h:56
Inline: True
```
```
In fs/splice.c (ffffffff81265be2)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81284654)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff8129594c)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812985d9)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff81338ee1)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8133a0ab)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/file.c (ffffffff8134a228)
Location: include/linux/highmem.h:56
Inline: True
```
```
In crypto/ahash.c (ffffffff813debdf)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81441527)
Location: include/linux/highmem.h:56
Inline: True
```
```
In lib/iov_iter.c (ffffffff81442714)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/acpi/osl.c (ffffffff81894eef)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579dc3)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/base/firmware_class.c (ffffffff815b285e)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff817353d0)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817677bf)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81774fa0)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff817caf1e)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8111c17e)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff811ed57d)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff81205024)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/userfaultfd.c (ffffffff8123fb3a)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8124d336)
Location: include/linux/highmem.h:56
Inline: True
```
```
In fs/splice.c (ffffffff812792a2)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81298366)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff812aa5af)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812ad06d)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff8134ec81)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8134fe4b)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In crypto/ahash.c (ffffffff813f7179)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff8145e741)
Location: include/linux/highmem.h:56
Inline: True
```
```
In lib/iov_iter.c (ffffffff8145fb64)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/acpi/osl.c (ffffffff818c963d)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a6303)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/base/firmware_class.c (ffffffff815e1c7e)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff8176857f)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817947cf)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff817a22e6)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff817fac36)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8111e01a)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff811f8da6)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff812106e4)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/userfaultfd.c (ffffffff8124b59f)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812594c6)
Location: include/linux/highmem.h:56
Inline: True
```
```
In fs/splice.c (ffffffff81286812)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff812a5e56)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff812b6dba)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9e99)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff81363751)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813648f2)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In crypto/ahash.c (ffffffff81403548)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff8146394e)
Location: include/linux/highmem.h:56
Inline: True
```
```
In lib/iov_iter.c (ffffffff81467534)
Location: include/linux/highmem.h:56
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81900ba5)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7227)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bac22)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc1b4)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/base/firmware_class.c (ffffffff815f68fb)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff81786e56)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817b29ef)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff817bfb75)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff8181b04f)
Location: include/linux/highmem.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8112980a)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff81211136)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff81227ba5)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
```
```
In mm/userfaultfd.c (ffffffff8126b895)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8127b663)
Location: include/linux/highmem.h:57
Inline: True
```
```
In fs/splice.c (ffffffff812a92d2)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff812c9386)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff812da773)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd863)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff8138849b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81389612)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In crypto/ahash.c (ffffffff8142bc78)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff8148f8ee)
Location: include/linux/highmem.h:57
Inline: True
```
```
In lib/iov_iter.c (ffffffff814918aa)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/acpi/osl.c (ffffffff8198aba5)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161de79)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8161f28b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816212eb)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8162267b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/base/firmware_class.c (ffffffff8165e85b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff817fd2e6)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff8182acbf)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81839725)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff81899ff8)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff811377a0)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff81231b36)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8124d687)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812903eb)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812a1f1c)
Location: include/linux/highmem.h:57
Inline: True
```
```
In fs/splice.c (ffffffff812cfe12)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff812f22c5)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff8130646a)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309e0f)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff813b729b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8441)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In crypto/ahash.c (ffffffff8145e985)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff814c4600)
Location: include/linux/highmem.h:57
Inline: True
```
```
In lib/iov_iter.c (ffffffff814c687c)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/acpi/osl.c (ffffffff819e74d5)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81657b86)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8165901b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b0a7)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c44b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b22b)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff81846b1a)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81874daf)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81883e5d)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff818ee562)
Location: include/linux/highmem.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff81142f40)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff81245306)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff81261aaa)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812a5388)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812b6c9f)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff812e5222)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81306cd2)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff8131bbfa)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f60f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff813d07eb)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813d19c1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff813ea717)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff8147c2f5)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff814d8cf1)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff814db00d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/acpi/osl.c (ffffffff81a22945)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677923)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8167905b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816797bb)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8167a6fb)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbaab)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170ae56)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff81872d7a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff8189566f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff818a4e6b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff8191bd26)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8114e291)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff81257346)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8127c75c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812c0b3d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812d3972)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff81303a22)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81328281)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/binfmt_elf.c (ffffffff813434ec)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346e44)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb40b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813fc4ec)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff81416b19)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814aa5e3)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81504ba4)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff8150691c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/acpi/osl.c (ffffffff81a929e9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac7dd)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad598)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af7f1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816afde4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816b10b6)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f56c4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f625c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817465b9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff818b6f5a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff818dfb8f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff818ef5c8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff8197e01b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff81159fa1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff812658d6)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8128c23d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812d28ed)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812e5502)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff81316aa2)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff8133b023)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffff81340b4b)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8135b92a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f152)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff814152db)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff814163cc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff81430a55)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814c52a3)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81522ce4)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff81524a2c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
```
```
In drivers/acpi/osl.c (ffffffff81aca1a9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d0278)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d24ea)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816d2ae4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816d3db6)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719ac4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171a65c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a709)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff818e98ba)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81911d3f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81921564)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff819b4a30)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8116a0e8)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/memory.c (ffffffff81295b73)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff812bf15a)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff81308799)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8131cea7)
Location: include/linux/highmem.h:137
Inline: True
```
```
In fs/splice.c (ffffffff813501f0)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81375a0b)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/io_uring.c (ffffffff8137c0a1)
Location: include/linux/highmem.h:137
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813a046c)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a3722)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff8146359b)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81464972)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff814805c7)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In crypto/ahash.c (ffffffff81524179)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81585c89)
Location: include/linux/highmem.h:137
Inline: True
```
```
In lib/iov_iter.c (ffffffff81589240)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/acpi/osl.c (ffffffff81bc27f9)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d5aec)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d667c)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bcfc4)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff819e3c92)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff819f56fe)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb85)
Location: include/linux/highmem.h:137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067231)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
```
In kernel/kexec_core.c (ffffffff81166828)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/memory.c (ffffffff812a0b16)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff812cad7a)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff8131456f)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff813283f7)
Location: include/linux/highmem-internal.h:147
Inline: True
```
```
In fs/aio.c (ffffffff813838df)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/coredump.c (ffffffff813b95c7)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eddb)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81480132)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff8149bcaa)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In lib/scatterlist.c (ffffffff815a2d69)
Location: include/linux/highmem-internal.h:147
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a58d3)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/acpi/osl.c (ffffffff81c3b847)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea4fc)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb0ac)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In net/core/sock.c (ffffffff819e3622)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff819f51be)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81aa8ac8)
Location: include/linux/highmem-internal.h:147
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In arch/x86/hyperv/hv_init.c (ffffffff831c4f5d)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/kexec_core.c (ffffffff811675c8)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/memory.c (ffffffff812a6456)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff812d1858)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff8131a71c)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8132e32b)
Location: include/linux/highmem-internal.h:142
Inline: True
```
```
In fs/aio.c (ffffffff8138a66d)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/verity/read_metadata.c (ffffffff813b060f)
Location: include/linux/highmem-internal.h:142
Inline: True
```
```
In fs/ecryptfs/read_write.c (ffffffff8148496b)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81485982)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff814a0dca)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In lib/scatterlist.c (ffffffff815a9c99)
Location: include/linux/highmem-internal.h:142
Inline: True
```
```
In lib/iov_iter.c (ffffffff815ac9e4)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/acpi/osl.c (ffffffff81c2e007)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/base/firmware_loader/main.c (ffffffff817cec91)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cf82e)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In net/core/sock.c (ffffffff819c96a2)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff819db346)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a93be5)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In arch/x86/hyperv/hv_init.c (ffffffff832a5c8d)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/kexec_core.c (ffffffff8118cd78)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/memory.c (ffffffff812e7916)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff81316f89)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff81367f4a)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8137bb4b)
Location: include/linux/highmem-internal.h:153
Inline: True
```
```
In fs/aio.c (ffffffff813d797d)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/verity/read_metadata.c (ffffffff814001ff)
Location: include/linux/highmem-internal.h:153
Inline: True
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbfeb)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff814dd0a2)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff814f8cd6)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In lib/scatterlist.c (ffffffff81612dde)
Location: include/linux/highmem-internal.h:153
Inline: True
```
```
In lib/iov_iter.c (ffffffff81616da1)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/acpi/osl.c (ffffffff81d4c926)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/base/firmware_loader/main.c (ffffffff818593a1)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81859f8e)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In net/core/sock.c (ffffffff81a78a22)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81a8a9c6)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81b4f02e)
Location: include/linux/highmem-internal.h:153
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In arch/x86/hyperv/hv_init.c (ffffffff83454d7c)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/kexec_core.c (ffffffff811bc418)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/memory.c (ffffffff81348ac6)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff813825ab)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff813e5692)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff813fb7dd)
Location: include/linux/highmem-internal.h:164
Inline: True
```
```
In fs/aio.c (ffffffff81461c61)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/verity/read_metadata.c (ffffffff8147401a)
Location: include/linux/highmem-internal.h:164
Inline: True
```
```
In fs/ecryptfs/read_write.c (ffffffff81569ceb)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8156b0a4)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff8158931b)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In lib/scatterlist.c (ffffffff816df472)
Location: include/linux/highmem-internal.h:164
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e5350)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/acpi/osl.c (ffffffff81f1c471)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199ff77)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a129e)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In net/core/sock.c (ffffffff81bec485)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81bfffe0)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81cdc98e)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In mm/memory.c (ffffffff813c0f43)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff813fc511)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/aio.c (ffffffff814f1e01)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d99b)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8160ef64)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In lib/scatterlist.c (ffffffff817cf6a2)
Location: include/linux/highmem-internal.h:164
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff820c44a1)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In net/core/sock.c (ffffffff81d98f08)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81daf3d0)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff81e9d3ee)
Location: include/linux/highmem-internal.h:164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In mm/memory.c (ffffffff813f5280)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8142f820)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ecryptfs/read_write.c (ffffffff8164584b)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81646df4)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In lib/scatterlist.c (ffffffff8180db52)
Location: include/linux/highmem-internal.h:167
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff82148281)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In net/core/datagram.c (ffffffff81e1f5d3)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
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
In mm/swapfile.c (ffffffff814693f4)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In lib/scatterlist.c (ffffffff81853802)
Location: include/linux/highmem-internal.h:167
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8222ac10)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In net/core/datagram.c (ffffffff81edcc83)
Location: include/linux/highmem-internal.h:167
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
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
In virt/kvm/kvm_main.c (ffff8000100be6d0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_map_gfn
```
```
In kernel/kexec_core.c (ffff8000101c9630)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffff8000102fc368)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffff80001032791c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffff800010378608)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffff80001038d890)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffff8000103cd444)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffff8000103fb928)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/io_uring.c (ffff800010400b40)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffff800010420f10)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104247c0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffff8000104f68d0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffff8000104f79b4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffff800010515560)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffff8000105bfe80)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffff80001062c874)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffff800010631b30)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108baaf0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcf7c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd694)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffff8000108be984)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d1ac)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e1d0)
Location: include/linux/highmem.h:81
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c6c8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffff800010b5cc60)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffff800010ba9820)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffff800010bbbbf4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffff800010c65188)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kmap(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/highmem.c (c0321a08)
Location: arch/arm/mm/highmem.c:34
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - mm/memory.c:__access_remote_vm
  - mm/swapfile.c:__do_sys_swapon
  - mm/userfaultfd.c:mcopy_atomic
  - fs/exec.c:copy_strings
  - fs/splice.c:write_pipe_buf
  - fs/aio.c:aio_read_events
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/readdir.c:fuse_readdir_cached
  - crypto/ahash.c:hash_walk_next
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/datagram.c:__skb_datagram_iter
  - net/ipv4/ip_output.c:ip_append_page
```
**Symbols:**

```
c0321a08-c0321a4c: kmap (STB_GLOBAL)
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
In arch/powerpc/mm/mem.c (c000000000087338)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:flush_icache_user_range
```
```
In kernel/kexec_core.c (c000000000231f48)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (c0000000003c7af0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (c0000000003fe698)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (c00000000046ac6c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (c000000000485028)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (c0000000004cf298)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (c0000000005031b0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (c00000000050a560)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (c00000000052fc84)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338a4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (c00000000063795c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (c000000000639158)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (c00000000065dd94)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In crypto/ahash.c (c000000000747d50)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (c0000000007cf450)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (c0000000007d2074)
Location: include/linux/highmem.h:81
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bf68)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095ec98)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (c00000000095f568)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (c000000000960e6c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (c0000000009ad474)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009ae754)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25100)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In net/core/sock.c (c000000000c7ed58)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (c000000000c94b68)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (c000000000d69550)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In mm/memory.c (ffffffe00020b83c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffe00022778c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffe000250010)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffe00025dbee)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In fs/splice.c (ffffffe00028a7cc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffe0002a96fc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffe0002ad0d0)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffe0002c190e)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffe000365550)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffe0003663e8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffe00037ec36)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffe000404edc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffe00045c96c)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffe00045e37e)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b538)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f076)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fa98)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570f62)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591d86)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe0005926fe)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d71be)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a7fc)
Location: include/linux/highmem.h:81
Inline: True
```
```
In net/core/sock.c (ffffffe00073cd72)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffe00074aa0a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffe0007cc880)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff811525c1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff8125df26)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8128481d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812caecd)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812ddae2)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff8130f082)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81333603)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffff8133912b)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81353f0a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357732)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d8bb)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8140e9ac)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff81429035)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814bd883)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff8151b2c4)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff8151d00c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
```
```
In drivers/acpi/osl.c (ffffffff81a69019)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695cc8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697f3a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81698534)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81699806)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffff816dfdf4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e098c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171edf9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff8188c63a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff818b1d3f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff818c1564)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff819548a0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff811458a1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff81250376)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8127668d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812bbe25)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812ce762)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff812ffc92)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81324273)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffff81329e5b)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81344bca)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813483e2)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe33b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813ff42c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff81419ab5)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814ae2a3)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff8150b5b4)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff8150d2fc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
```
```
In drivers/acpi/osl.c (ffffffff81a25ad9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816736b8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8167592a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81675f24)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816771f6)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba434)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bafcc)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8229)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff81843fba)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff8186bc8f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff8187b4a4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff8190e390)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff81150471)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff8125bcc6)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8128262d)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812c8cdd)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812db8f2)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff8130ce72)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff813310d3)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffff81336bfb)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813519da)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81355202)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff8140ac3b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8140bd2c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff814251d5)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814b9913)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81517354)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff8151909c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
```
```
In drivers/acpi/osl.c (ffffffff81ad5429)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3f38)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c61aa)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816c67a4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816c7a76)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e05c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175dbc9)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff818de71a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81902d3f)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff81912564)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff819bf070)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
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
In kernel/kexec_core.c (ffffffff8115d2b0)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/memory.c (ffffffff8126b643)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__access_remote_vm
```
```
In mm/swapfile.c (ffffffff8129231b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (ffffffff812d99d8)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812ec8a2)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/splice.c (ffffffff8131e690)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/aio.c (ffffffff81343cb7)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (ffffffff81349cca)
Location: include/linux/highmem.h:81
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81364f7a)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813687e2)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ecryptfs/read_write.c (ffffffff814208f4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff814219bb)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/readdir.c (ffffffff8143c0aa)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In crypto/ahash.c (ffffffff814d230c)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In lib/scatterlist.c (ffffffff81530ac3)
Location: include/linux/highmem.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff8153288b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
```
```
In drivers/acpi/osl.c (ffffffff81ae18ee)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de4f1)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e06bd)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816e0ca7)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816e1f79)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffff81728125)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81728ca2)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817791d5)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/firmware/efi/capsule.c (ffffffff818fb1df)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81923cee)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/datagram.c (ffffffff819336c4)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/ipv4/ip_output.c (ffffffff819c8a0b)
Location: include/linux/highmem.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
