# Function: <code>__get_unaligned_be16</code>

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
In fs/ecryptfs/crypto.c (c06b5ff8)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
```
```
In block/partitions/ldm.c (c07ae7f4)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/scsi/scsi.c (c0a43468)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (c0a49938)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (c0a54c90)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (c0a5c350)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (c0a7215c)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (c0addba8)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/firmware/dmi_scan.c (c15a6830)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In net/core/filter.c (c0d10a4c)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (c0d85fc8)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (c0ddfc34)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (c15bd1bc)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffe000367054)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
```
```
In block/partitions/ldm.c (ffffffe00043e7e4)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/scsi/scsi.c (ffffffe0005d82e0)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dd9b8)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffe0005e7724)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffe0005ee2f2)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffe000600fb2)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d23c)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/filter.c (ffffffe000778a60)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffe0007daee0)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000826a94)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffe00004679c)
Location: include/linux/unaligned/be_byteshift.h:7
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
