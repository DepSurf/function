# Function: <code>get_unaligned_le32</code>

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
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/decompress_unlz4.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/hexdump.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/lzo/lzo1x_compress.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/lzo/lzo1x_decompress_safe.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:12
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
In fs/fat/inode.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813bbfc7)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/partitions/msdos.c (ffffffff81418680)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/decompress_unlz4.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/hexdump.c (ffffffff814491e5)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8145593e)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814560d6)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:12
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
In fs/fat/inode.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813d34d1)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/partitions/msdos.c (ffffffff81433bb0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/decompress_unlz4.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/hexdump.c (ffffffff81467bd5)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814742fe)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81474a96)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:12
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
In fs/fat/inode.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813e65ce)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In crypto/aes_generic.c (ffffffff8140faee)
Location: include/linux/unaligned/access_ok.h:12
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
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8146d434)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814795f8)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81479caa)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799caf)
Location: include/linux/unaligned/access_ok.h:12
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82110279)
Location: include/linux/unaligned/access_ok.h:12
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
In fs/fat/inode.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d7b0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In crypto/aes_generic.c (ffffffff8143a555)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81499764)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814a6998)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814a704a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814b8496)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8181004f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8271a679)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff813ae845)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8143eef4)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff8146e076)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814a0f5e)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff814ce98a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff814d4a23)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814dc568)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814e6527)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814ef285)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff816eaa41)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81717835)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82736ee5)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81859eea)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82744e08)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff813c7a3f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be0a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_dfa
```
```
In crypto/aes_generic.c (ffffffff8148ba26)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814bb31e)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff814e327a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff814e9473)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814f0fd8)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814fa5d7)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81502fab)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8170e4f1)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81739e85)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0e11)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8187918a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff828ff12e)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff813f260c)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8148877a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814b9119)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814e99a7)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8150f600)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffff815160b3)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8151df09)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81527d67)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815311f9)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff81749cb2)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81775e9a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c45b)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818beaae)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8291bd26)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff8140c50f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814a262a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814d1eb9)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff81502d6b)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8152d5e0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8152f24d)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153ed99)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81548bf7)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81552089)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8176de02)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81799e05)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915e2a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f15fe)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82925bbe)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff81459437)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff814fda2b)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff815635bf)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff81592ef8)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815a33ea)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815a3f29)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d4537)
Location: include/linux/unaligned/access_ok.h:13
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
In lib/xz/xz_dec_bcj.c (ffffffff815db56a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlz4.c (ffffffff82d0ba65)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817d98f5)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81830411)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c345)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27ff6)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c603e)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff81475787)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff8151ac8b)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8157e6fc)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815afae2)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815bef25)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815bfac3)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815f21bc)
Location: include/linux/unaligned/access_ok.h:13
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
In lib/xz/xz_dec_bcj.c (ffffffff815f91bb)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/pldmfw/pldmfw.c (ffffffff8160b190)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff82ff9049)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817ee745)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81841087)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b435)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8301670e)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c5f7e)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff8147b1f7)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In security/apparmor/policy_unpack.c (ffffffff815226bd)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8158629a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815ba915)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815c9b95)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d3cb7)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815dbc75)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee280)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff83203c5c)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/base/regmap/regmap.c (ffffffff817d2ff5)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81824277)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff8184dd45)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff832216b7)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819aaf06)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff814d2817)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/aes_generic.c (ffffffff815b7832)
Location: include/asm-generic/unaligned.h:30
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
In crypto/crc32c_generic.c (ffffffff815b8e5e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff815ebcc3)
Location: include/asm-generic/unaligned.h:30
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/crypto/aes.c (ffffffff81621015)
Location: include/asm-generic/unaligned.h:30
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
In lib/xxhash.c (ffffffff8162971b)
Location: include/asm-generic/unaligned.h:30
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
In lib/lzo/lzo1x_compress.c (ffffffff81633797)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8163ea12)
Location: include/asm-generic/unaligned.h:30
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
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81643644)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff816473ad)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In lib/pldmfw/pldmfw.c (ffffffff8165b330)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff832eb8c2)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/pci/vpd.c (ffffffff816ab56e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
```
```
In drivers/base/regmap/regmap.c (ffffffff8185e515)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff818afaae)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff818db3b5)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8330b105)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a589d6)
Location: include/asm-generic/unaligned.h:30
Inline: True
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
In fs/fat/inode.c (ffffffff8155f845)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/aes_generic.c (ffffffff81660b62)
Location: include/asm-generic/unaligned.h:30
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
In crypto/crc32c_generic.c (ffffffff816621ee)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8169bcc4)
Location: include/asm-generic/unaligned.h:30
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/crypto/aes.c (ffffffff816ef255)
Location: include/asm-generic/unaligned.h:30
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
In lib/xxhash.c (ffffffff816fa92b)
Location: include/asm-generic/unaligned.h:30
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
In lib/lzo/lzo1x_compress.c (ffffffff817052fc)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/common/entropy_common.c (ffffffff81709d3e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81718cbc)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81746ac4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81750604)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175488b)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81759dd1)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8175d5dd)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In lib/pldmfw/pldmfw.c (ffffffff817741b0)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In lib/decompress_unlz4.c (ffffffff834a3295)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In drivers/pci/vpd.c (ffffffff817ce590)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
```
```
In drivers/base/regmap/regmap.c (ffffffff819a57e5)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff819faa2b)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2e3b4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff834c4a50)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc86f0)
Location: include/asm-generic/unaligned.h:30
Inline: True
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
In fs/fat/inode.c (ffffffff81601b55)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/aes_generic.c (ffffffff8171aa02)
Location: include/asm-generic/unaligned.h:30
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
In crypto/crc32c_generic.c (ffffffff8171c17e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8175ad1d)
Location: include/asm-generic/unaligned.h:30
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/crypto/aes.c (ffffffff817e0065)
Location: include/asm-generic/unaligned.h:30
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
In lib/xxhash.c (ffffffff817ed3ab)
Location: include/asm-generic/unaligned.h:30
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
In lib/lzo/lzo1x_compress.c (ffffffff817f7f3c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e0fc)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8185e68b)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81874764)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878f5c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8188330c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff8188482e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8188aafd)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In lib/pldmfw/pldmfw.c (ffffffff818a4ca0)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In drivers/pci/vpd.c (ffffffff818ee050)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19535)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81b78a3b)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf604)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff83f04e8a)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d728f5)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
```
In lib/decompress_unlz4.c (ffffffff83f19837)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/fat/inode.c (ffffffff81639a47)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/aes_generic.c (ffffffff81756282)
Location: include/asm-generic/unaligned.h:30
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
In crypto/crc32c_generic.c (ffffffff8175791e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff81798bc8)
Location: include/asm-generic/unaligned.h:30
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/crypto/aes.c (ffffffff8181f7e7)
Location: include/asm-generic/unaligned.h:30
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
In lib/xxhash.c (ffffffff8182d60b)
Location: include/asm-generic/unaligned.h:30
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
In lib/lzo/lzo1x_compress.c (ffffffff8183832c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ec0c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8189f23b)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff818b54c4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b9d0c)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c5861)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff818c6d3e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff818ccfd4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In lib/pldmfw/pldmfw.c (ffffffff818e7aa8)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In drivers/pci/vpd.c (ffffffff81931530)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
```
```
In drivers/base/regmap/regmap.c (ffffffff81b68225)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc6cb)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff81c062f4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
```
```
In drivers/firmware/dmi_scan.c (ffffffff8372ae3a)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81de0695)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
```
In lib/decompress_unlz4.c (ffffffff837400c7)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/fat/inode.c (ffffffff81672f37)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/aes_generic.c (ffffffff81798242)
Location: include/asm-generic/unaligned.h:30
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
In crypto/crc32c_generic.c (ffffffff8179981e)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff817dc5f8)
Location: include/asm-generic/unaligned.h:30
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In lib/crypto/aes.c (ffffffff81865767)
Location: include/asm-generic/unaligned.h:30
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
In lib/xxhash.c (ffffffff8187f19b)
Location: include/asm-generic/unaligned.h:30
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
In lib/lzo/lzo1x_compress.c (ffffffff81889eec)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff818a07cc)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f0dfb)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81907084)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190b8cc)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917421)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff819188fe)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: include/asm-generic/unaligned.h:30
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8191ebc4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192eb10)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
```
```
In drivers/pci/vpd.c (ffffffff8197a050)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbbf65)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_le_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_le
```
```
In drivers/scsi/scsicam.c (ffffffff81c212fb)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_partsize
  - drivers/scsi/scsicam.c:scsi_partsize
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5b0a4)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
```
```
In drivers/firmware/dmi_scan.c (ffffffff8395edfa)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e96655)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
```
In lib/decompress_unlz4.c (ffffffff83974b77)
Location: include/asm-generic/unaligned.h:30
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/fat/inode.c (ffff8000104ed380)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffff800010598250)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffff8000105ce288)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffff800010604bd4)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffff800010639718)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffff80001063b1d8)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffff80001064b444)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffff800010654eb8)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffff80001065ddec)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffff800010970b9c)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a4030)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58b64)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
```
```
In drivers/firmware/arm_scmi/power.c (ffff800010b58e94)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (ffff800010b59410)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b797ec)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffff8000114b6da4)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (c06aaf4c)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (c074934c)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (c077bd6c)
Location: include/linux/unaligned/le_struct.h:12
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
In crypto/crc32c_generic.c (c077d4a4)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (c07afeb4)
Location: include/linux/unaligned/le_struct.h:12
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (c07df0d0)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (c07e1a4c)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/xxhash.c (c07e9858)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/lzo/lzo1x_compress.c (c07f6864)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/lzo/lzo1x_decompress_safe.c (c07f69f8)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/lz4/lz4_decompress.c (c07f9158)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/huf_decompress.c (c07faccc)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c07ffee4)
Location: include/linux/unaligned/le_struct.h:12
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
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (c0803f18)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (c08044c8)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/xz/xz_dec_bcj.c (c0807534)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (c0a458f0)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (c0a72d38)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/core/hcd.c (c0af3d68)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/firmware/dmi_scan.c (c15a6744)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39450)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
```
```
In drivers/firmware/arm_scmi/power.c (c0c3a118)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (c0c3a55c)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/platform/chrome/cros_ec_proto.c (c0c5f128)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
```
```
In lib/decompress_unlz4.c (c15bc30c)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
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
In fs/fat/inode.c (c00000000062bf34)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (c00000000070eca8)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (c000000000759f34)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (c0000000007a0968)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (c0000000007e01bc)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (c0000000007e2ae4)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (c000000000804d80)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (c000000000810000)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (c000000000a2a090)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (c000000000a697a4)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In lib/decompress_unlz4.c (c0000000013c9658)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffe00035d766)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e4cba)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffe000412b98)
Location: include/linux/unaligned/le_struct.h:12
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
In crypto/crc32c_generic.c (ffffffe000414670)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffe00043fa12)
Location: include/linux/unaligned/le_struct.h:12
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffe000466260)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffe0004681b6)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/xxhash.c (ffffffe00046fc96)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/lzo/lzo1x_compress.c (ffffffe0004771f6)
Location: include/linux/unaligned/le_struct.h:12
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
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
```
```
In lib/zstd/decompress.c (ffffffe00048317a)
Location: include/linux/unaligned/le_struct.h:12
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
In lib/zstd/entropy_common.c (ffffffe00048833e)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b7f2)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffe0005da31e)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In lib/decompress_unlz4.c (ffffffe000045998)
Location: include/linux/unaligned/le_struct.h:12
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
```
In lib/siphash.c (ffffffe0008bbfe4)
Location: include/linux/unaligned/le_struct.h:12
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
In fs/fat/inode.c (ffffffff81404aef)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8149ac0a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814ca499)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814fb34b)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81525bc0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8152782d)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81537379)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815411d7)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a669)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff817224f2)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff8174938c)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb37e)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8189292e)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8290a8c2)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff813f556f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b62a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814baeb9)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814eb85b)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81515ea0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff81517b0d)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81527659)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815314b7)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a949)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff816fb922)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff8172af7c)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/net/vxlan.c (ffffffff8176ca95)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2c1a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In lib/decompress_unlz4.c (ffffffff82902c10)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff81401e6f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff81496caa)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814c6529)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff814f73db)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff81521c50)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff815238bd)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815330b9)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8153cf17)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815463a9)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff817612c2)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ec85)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff8291045f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e642e)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff8292020c)
Location: include/linux/unaligned/access_ok.h:13
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
In fs/fat/inode.c (ffffffff81417e3f)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In security/apparmor/policy_unpack.c (ffffffff814aed7a)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_blob
  - security/apparmor/policy_unpack.c:unpack_u32
```
```
In crypto/aes_generic.c (ffffffff814deff9)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In block/partitions/msdos.c (ffffffff8151043b)
Location: include/linux/unaligned/access_ok.h:13
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
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_minix
```
```
In lib/hexdump.c (ffffffff8153b5d0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/crypto/aes.c (ffffffff8153d23d)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8154cee9)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81556d47)
Location: include/linux/unaligned/access_ok.h:13
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
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815601d9)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsicam.c (ffffffff8177c922)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8db5)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (ffffffff82916e8c)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:save_mem_devices
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819030ae)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
```
```
In lib/decompress_unlz4.c (ffffffff82926c30)
Location: include/linux/unaligned/access_ok.h:13
Inline: True
Inline callers:
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
```
</details>
</li>
</ul>

## Differences
