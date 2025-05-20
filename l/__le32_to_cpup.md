# Function: <code>__le32_to_cpup</code>

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
In init/do_mounts_rd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/decompress_unlz4.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/hexdump.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/lzo/lzo1x_compress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
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
In init/do_mounts_rd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810779ae)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/fat/inode.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813bbfc7)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/partitions/msdos.c (ffffffff81418680)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/decompress_unlz4.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/hexdump.c (ffffffff814491e5)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8145593e)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814560d6)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1adf)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8172edfc)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107b79e)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/fat/inode.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813d34d1)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/partitions/msdos.c (ffffffff81433bb0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/decompress_unlz4.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/hexdump.c (ffffffff81467bd5)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814742fe)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81474a96)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d075f)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8176203c)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81079f5e)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/fat/inode.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813e65ce)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In crypto/aes_generic.c (ffffffff8140faee)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In block/partitions/msdos.c (ffffffff81440978)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8146d434)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814795f8)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81479caa)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e4df1)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81780671)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799caf)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82110279)
Location: include/uapi/linux/byteorder/little_endian.h:55
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108064e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/fat/inode.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d7b0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In crypto/aes_generic.c (ffffffff8143a555)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In block/partitions/msdos.c (ffffffff8146d009)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81499764)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814a6998)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814a704a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814b8496)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814b90d9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8175160f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
```
```
In drivers/mmc/core/sdio_io.c (ffffffff817f6c31)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8181004f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8271a679)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108389e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff813ae845)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8143eef4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff8146e076)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In crypto/crc32c_generic.c (ffffffff8146f2ee)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814a0f5e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff814ce98a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff814d4a23)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814dbeba)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814dc568)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814e6527)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814eba18)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff814ed32d)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814ef285)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff816eaa41)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81717835)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81792210)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8184024f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff82736ee5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81859eea)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82744e08)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108a56e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff813c7a3f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be0a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff8148ba26)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In crypto/crc32c_generic.c (ffffffff8148cc9e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814bb31e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff814e327a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff814e9473)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814f092a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814f0fd8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814fa5d7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814ff768)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff8150108e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81502fab)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8170e4f1)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81739e85)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b87e0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8186c1ff)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0e11)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8187918a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff828ff12e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e36e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff813f260c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8148877a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814b9119)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In crypto/crc32c_generic.c (ffffffff814ba38e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814e99a7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8150f600)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff815160b3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8151d610)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8151df09)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81527d67)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8152d930)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff8152f1e5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815311f9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff81749cb2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81775e9a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f73b3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818b0080)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c45b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818beaae)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8291bd26)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108efce)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff8140c50f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814a262a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814d1eb9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814d315e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff81502d6b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8152d5e0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8152f24d)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff81536af3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8153e4a0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153ed99)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81548bf7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8154e7c0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff81550075)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81552089)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8176de02)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81799e05)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81828213)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818e2530)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915e2a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f15fe)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82925bbe)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810953ee)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/fname.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff81459437)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff814fda2b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:verify_header
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff81531049)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff815323ee)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff815635bf)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/hexdump.c (ffffffff81591239)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff81592ef8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff8159b05e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815a2aaf)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815a33ea)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815a3f29)
Location: include/uapi/linux/byteorder/little_endian.h:56
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
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
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
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
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
In lib/zstd/fse_compress.c (ffffffff815ac803)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
```
In lib/zstd/compress.c (ffffffff815b95a1)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
```
```
In lib/zstd/entropy_common.c (ffffffff815cc6e2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d4537)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/xz/xz_dec_stream.c (ffffffff815d94ea)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815db56a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlz4.c (ffffffff82d0ba65)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817d98f5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81830411)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c345)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1e86)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818facd7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b55e0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27ff6)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c603e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109462e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/fname.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff81475787)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff8151ac8b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:verify_header
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff8154df99)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8154f33e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8157e6fc)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/hexdump.c (ffffffff815addde)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815afae2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff815b6a4e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815be5b4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815bef25)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815bfac3)
Location: include/uapi/linux/byteorder/little_endian.h:56
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
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
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
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
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
In lib/zstd/fse_compress.c (ffffffff815c8308)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
```
In lib/zstd/compress.c (ffffffff815d6a86)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
```
```
In lib/zstd/entropy_common.c (ffffffff815ea267)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815f21bc)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/xz/xz_dec_stream.c (ffffffff815f713f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815f91bb)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/pldmfw/pldmfw.c (ffffffff8160b190)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff82ff9049)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817ee745)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81841087)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b435)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fada6)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81903817)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b7ba0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff8301670e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c5f7e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81094f9e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/fname.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff8147b1f7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff815226bd)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff815566be)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff81557bae)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8158629a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/hexdump.c (ffffffff815b8a76)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815ba915)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff815c18ab)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815c9234)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815c9b95)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d3cb7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff815d836c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff815d9be1)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815dbc75)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee280)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff83203c5c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817d2ff5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81824277)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8184dd45)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddb66)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e7037)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8199c330)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff832216b7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819aaf06)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810a4f3e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
```
```
In block/partitions/msdos.c (ffffffff815ebc7a)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffff816451e0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81979686)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819833f7)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81a48d10)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810ba06e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
```
```
In block/partitions/msdos.c (ffffffff8169bc94)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffff8175af3e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6d76)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81ade89e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81bb6eff)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810d5dce)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
```
```
In block/partitions/msdos.c (ffffffff8175aced)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffff8188833e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61af6)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c69d23)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81d5b9ff)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e130e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
```
```
In block/partitions/msdos.c (ffffffff81798b9c)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffff818ca99b)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8e94)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd10c2)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81dc647f)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e9b8e)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
```
```
In block/partitions/msdos.c (ffffffff817dc5cc)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffff8191c55b)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dd74)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d86082)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81e7edbf)
Location: include/uapi/linux/byteorder/little_endian.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
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
In arch/arm64/kernel/module-plts.c (ffff8000100a2efc)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/arm64/kernel/module-plts.c:module_emit_veneer_for_adrp
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffff8000104ed380)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffff800010598250)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffff8000105ce288)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffff8000105cf754)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffff800010604bd4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffff800010639718)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffff80001063b1d8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffff8000106435a4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffff80001064abac)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffff80001064b444)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffff800010654eb8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffff80001065a900)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffff80001065c3b4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffff80001065ddec)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffff800010970b9c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a6288c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffff800010b3cc64)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a4030)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58b64)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
```
```
In drivers/firmware/arm_scmi/power.c (ffff800010b58e94)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (ffff800010b59410)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b797ec)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffff8000114b6da4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In block/partitions/msdos.c (c07afab8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (c0805848)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In drivers/usb/host/ehci-hcd.c (c0b2a558)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (c0b35154)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (c0c172e4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/siphash.c (c0e8e70c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (c00000000062bf34)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (c00000000070eca8)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (c000000000759f34)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (c00000000075b794)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (c0000000007a0968)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (c0000000007e01bc)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (c0000000007e2ae4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (c0000000007eea7c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (c0000000007f9130)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (c0000000007f9340)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (c000000000804d80)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (c00000000080b7d4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (c00000000080d98c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (c000000000810000)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (c000000000a2a090)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (c000000000a697a4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b324d4)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (c000000000c39e3c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (c0000000013c9658)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In block/partitions/msdos.c (ffffffe00043f71e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
```
```
In lib/xz/xz_dec_stream.c (ffffffe000489e58)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067e3c2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffe000713f80)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/siphash.c (ffffffe0008bbd5e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df8e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff81404aef)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8149ac0a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814ca499)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814cb73e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814fb34b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81525bc0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8152782d)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff8152f0d3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81536a80)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81537379)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815411d7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81546da0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff81548655)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a669)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff817224f2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff8174938c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8175eef5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817e05f3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81885ef0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb37e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8189292e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8290a8c2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107ca9e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff813f556f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b62a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814baeb9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814bc15e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814eb85b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81515ea0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff81517b0d)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff8151f3b3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81526d60)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81527659)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815314b7)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81537080)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff81538935)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a949)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff816fb922)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff8172af7c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8173ed89)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/net/vxlan.c (ffffffff8176ca95)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2c1a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82902c10)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df3e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff81401e6f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff81496caa)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814c6529)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814c77ce)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814f73db)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81521c50)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815238bd)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff8152ae13)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815327c0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815330b9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8153cf17)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81542ae0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff81544395)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815463a9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff817612c2)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ec85)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181d093)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818d7390)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff8291045f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e642e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8292020c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109031e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/sysfs.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In fs/fat/inode.c (ffffffff81417e3f)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814aed7a)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814deff9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814e029e)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8151043b)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8153b5d0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8153d23d)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
```
```
In lib/xxhash.c (ffffffff81544b73)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh32_digest
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
  - lib/xxhash.c:xxh32
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8154c5f0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8154cee9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81556d47)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8155c910)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/xz/xz_dec_stream.c (ffffffff8155e1c5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815601d9)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8177c922)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8db5)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81836de3)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_get_frame
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818f3eb0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_readl
```
```
In drivers/firmware/dmi_scan.c (ffffffff82916e8c)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819030ae)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82926c30)
Location: include/uapi/linux/byteorder/little_endian.h:56
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
</details>
</li>
</ul>

## Differences
