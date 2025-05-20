# Function: <code>__get_unaligned_cpu64</code>

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
In security/apparmor/policy_unpack.c (c074a7e8)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/hexdump.c (c07df038)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (c07e97b0)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
```
```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
```
```
In lib/zstd/decompress.c (c0800028)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/fse_decompress.c (0)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
```
```
In drivers/ata/libata-core.c (c0a6cca0)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (c0a72d6c)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/firmware/dmi_scan.c (c15a6750)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38b60)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
```
```
In drivers/firmware/arm_scmi/sensors.c (c0c3a910)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
```
```
In net/core/sock.c (c0cc8b88)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (c0da1f24)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In security/apparmor/policy_unpack.c (ffffffe0003e5e30)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/hexdump.c (ffffffe000466098)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/xxhash.c (ffffffe00046fbc0)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/xxhash.c:xxh64_digest
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
  - lib/xxhash.c:xxh64
```
```
In lib/lz4/lz4_decompress.c (ffffffe00047a260)
Location: include/linux/unaligned/packed_struct.h:22
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
In lib/zstd/huf_decompress.c (ffffffe00047bc80)
Location: include/linux/unaligned/packed_struct.h:22
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
```
```
In lib/zstd/decompress.c (ffffffe000483282)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
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
```
```
In lib/zstd/fse_decompress.c (ffffffe0004888da)
Location: include/linux/unaligned/packed_struct.h:22
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
```
```
In drivers/ata/libata-core.c (ffffffe0005fcd08)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/usb/core/hcd.c (ffffffe0006401c8)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In net/core/sock.c (ffffffe00073d8a8)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2bf8)
Location: include/linux/unaligned/packed_struct.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
```
In lib/siphash.c (ffffffe0008bbf06)
Location: include/linux/unaligned/packed_struct.h:22
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
