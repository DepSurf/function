# Function: <code>__get_unaligned_cpu16</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06aaec8)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (c0749278)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (c07df16c)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (c07f6e10)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (c07f8bc8)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/huf_decompress.c (c07faf94)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
```
```
In lib/zstd/decompress.c (c080001c)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In drivers/tty/vt/vc_screen.c (c096d0e4)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (c0a6b1d0)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (c0a72d44)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (c15a6990)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035d766)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e4bd4)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffe0004662ea)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffe000477736)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffe000479b58)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/huf_decompress.c (ffffffe00047c6c8)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
```
```
In lib/zstd/decompress.c (ffffffe00048326e)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In drivers/tty/vt/vc_screen.c (ffffffe00053cde2)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffe0005fb6ba)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In lib/siphash.c (ffffffe0008bc14e)
Location: include/linux/unaligned/packed_struct.h:10
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
```
</details>
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
