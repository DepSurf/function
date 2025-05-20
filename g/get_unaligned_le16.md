# Function: <code>get_unaligned_le16</code>

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
In fs/fat/inode.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/lz4/lz4_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
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
In fs/fat/inode.c (ffffffff81330b83)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff813bb6e1)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814560a5)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fe2591)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
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
In fs/fat/inode.c (ffffffff813468d3)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff813d2bf1)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81474a65)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8202036e)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
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
In fs/fat/inode.c (ffffffff8135b27d)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff813e5781)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81479c31)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8147d885)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff82102e1c)
Location: include/linux/unaligned/access_ok.h:7
Inline: True
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
In fs/fat/inode.c (ffffffff8137ff80)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8140c971)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814a6fd1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814aa52a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/huf_decompress.c (ffffffff814abd17)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8270c4fd)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
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
In fs/fat/inode.c (ffffffff813ae7f1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e2f1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff814cea15)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814dc46d)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814df8b6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/huf_decompress.c (ffffffff814e0faf)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814e6656)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In drivers/acpi/battery.c (ffffffff815cf8d3)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8161fd86)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff8170f525)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81717835)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82737096)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff813c79eb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b1b1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff814e3305)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814f0edd)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814f2ac9)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff814f4d45)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814fa706)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In drivers/acpi/battery.c (ffffffff815e8eb3)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8163d04e)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff817319d5)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81739e85)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0fc2)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff813f25b8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814886b1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff8150f68f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8151e1ba)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8151fb11)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff81521da4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81527ea2)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/acpi/battery.c (ffffffff8161a988)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8167150b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff8176d197)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81775e9a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c614)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff8140c4bb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2561)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff8152d66f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153f04a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815409a1)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff81542c34)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81548d32)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/acpi/battery.c (ffffffff8163c3b8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81693bdf)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff81791207)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81799e05)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915fe7)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff81459551)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff814fdc46)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (ffffffff815912c6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815a369b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815a57e3)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815aa000)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/fse_compress.c (ffffffff815abd71)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress.c (ffffffff815c9217)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
```
In lib/zstd/huf_decompress.c (ffffffff815ce51f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d466f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In drivers/acpi/battery.c (ffffffff816ea1a8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8174684c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/base/regmap/regmap.c (ffffffff817d98c5)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff818562e3)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c345)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935e82)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27edb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff814758a1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff8151aea6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (ffffffff815ade6b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815bf1d6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815c15bb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815c5ae8)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/fse_compress.c (ffffffff815c7876)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress.c (ffffffff815e6d8a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
```
In lib/zstd/huf_decompress.c (ffffffff815ec104)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815f22f4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff8160aa34)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_image
  - lib/pldmfw/pldmfw.c:pldm_parse_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/acpi/battery.c (ffffffff81707998)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81761c7f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write_buf
```
```
In drivers/base/regmap/regmap.c (ffffffff817ee715)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81866563)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b435)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c23ac4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff830165f3)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff8147b320)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff815215e6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:unpack_str
```
```
In lib/hexdump.c (ffffffff815b8b01)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815c9e3e)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815cb7b3)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff815cdae6)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d3ddb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee775)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/acpi/battery.c (ffffffff816e8ad8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8174594f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write_buf
```
```
In drivers/base/regmap/regmap.c (ffffffff817d2fc5)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81848b8d)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8184dd45)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c15a8a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8322159c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff814d294a)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81634309)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81636153)
Location: include/asm-generic/unaligned.h:25
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
In lib/zstd/huf_decompress.c (ffffffff81638136)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8163eb48)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff8165b825)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/pci/vpd.c (ffffffff816aad60)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_size
```
```
In drivers/base/regmap/regmap.c (ffffffff8185e505)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff818d5b3d)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff818db3b5)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d24440)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8330afea)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In fs/fat/inode.c (ffffffff8155f987)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81705e9d)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81707cb1)
Location: include/asm-generic/unaligned.h:25
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8174baa5)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175191f)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8175a3d5)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff817745ea)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/pci/vpd.c (ffffffff817cdd12)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_available
```
```
In drivers/base/regmap/regmap.c (ffffffff819a5795)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81a26c1e)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2e3b4)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81ef028c)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff834c4931)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In fs/fat/inode.c (ffffffff81601d37)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff817f8b5d)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff817fb851)
Location: include/asm-generic/unaligned.h:25
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8187062a)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875b9f)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81883be5)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff818a50fa)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/pci/vpd.c (ffffffff818ed672)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_available
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19555)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81ba88de)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf604)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb4e9e)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff83f04c04)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In fs/fat/inode.c (ffffffff81639c37)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81838f31)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8183c19a)
Location: include/asm-generic/unaligned.h:25
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818b130a)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6874)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c6105)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff818e7f0a)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/pci/vpd.c (ffffffff81930b72)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_available
```
```
In drivers/base/regmap/regmap.c (ffffffff81b68245)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81bffffe)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81c062f4)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c50e)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8372abc4)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In fs/fat/inode.c (ffffffff81673127)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8188aaf1)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8188dd5a)
Location: include/asm-generic/unaligned.h:25
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
In lib/zstd/decompress/huf_decompress.c (ffffffff81902eca)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81908434)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917cc5)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192eff9)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldmfw_op_pci_match_record
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/pci/vpd.c (ffffffff819795a2)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_available
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbbf85)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_le
```
```
In drivers/ata/libata-core.c (ffffffff81c5606e)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5b0a4)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd225e)
Location: include/asm-generic/unaligned.h:25
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff8395eb84)
Location: include/asm-generic/unaligned.h:25
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In fs/fat/inode.c (ffff8000104ed334)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffff80001059813c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffff8000106397a8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffff80001064b6d0)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffff80001064d5e0)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffff80001064fc14)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffff800010654ff4)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/acpi/battery.c (ffff8000107a7d20)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffff800010867f2c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffff80001099afc8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffff8000109a4334)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a4250)
Location: include/linux/unaligned/access_ok.h:8
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06aaec8)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (c07df16c)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (c07f6e10)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (c07f8bc8)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
```
```
In lib/zstd/decompress.c (c080001c)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (c0a6b1d0)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (c0a72d44)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (c15a6990)
Location: include/linux/unaligned/le_struct.h:7
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062bedc)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (c00000000070eb40)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (c0000000007e026c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (c0000000007f9840)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (c0000000007fb918)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (c0000000007fe4a4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (c000000000804ee0)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/tty/vt/vc_screen.c (c0000000009074c8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (c000000000a5e5d8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (c000000000a697a4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
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
In fs/fat/inode.c (ffffffe00035d766)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffe0004662ea)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffe000477736)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffe000479b58)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
```
```
In lib/zstd/decompress.c (ffffffe00048326e)
Location: include/linux/unaligned/le_struct.h:7
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
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffe0005fb6ba)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/le_struct.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In lib/siphash.c (ffffffe0008bc14e)
Location: include/linux/unaligned/le_struct.h:7
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81404a9b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8149ab41)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff81525c4f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153762a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81538f81)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff8153b214)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81541312)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/tty/vt/vc_screen.c (ffffffff8165965f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/nvme/host/trace.c (ffffffff8174938c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81756347)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8175eef5)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb53b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff813f551b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b561)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff81515f2f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8152790a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81529261)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff8152b4f4)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815315f2)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/tty/vt/vc_screen.c (ffffffff816399df)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/nvme/host/trace.c (ffffffff8172af7c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
```
```
In drivers/ata/libata-core.c (ffffffff817361e7)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8173ed89)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2dd7)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff81401e1b)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff81496be1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff81521cdf)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153336a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81534cc1)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff81536f54)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8153d052)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/acpi/battery.c (ffffffff816301f8)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81687a1f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff81786087)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ec85)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8291061c)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
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
In fs/fat/inode.c (ffffffff81417deb)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814aecb1)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_str
  - security/apparmor/policy_unpack.c:unpack_array
  - security/apparmor/policy_unpack.c:unpack_nameX
```
```
In lib/hexdump.c (ffffffff8153b65f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8154d19a)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8154eaf1)
Location: include/linux/unaligned/access_ok.h:8
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
In lib/zstd/huf_decompress.c (ffffffff81550d84)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81556e82)
Location: include/linux/unaligned/access_ok.h:8
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
In drivers/acpi/battery.c (ffffffff8164a538)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff816a200f)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/ata/libata-core.c (ffffffff8179fed7)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_log_supported
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8db5)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82917049)
Location: include/linux/unaligned/access_ok.h:8
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
</details>
</li>
</ul>

## Differences
