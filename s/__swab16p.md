# Function: <code>__swab16p</code>

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
In kernel/bpf/core.c (ffffffff811725c7)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff81306901)
Location: include/uapi/linux/swab.h:154
Inline: True
```
```
In block/partitions/ldm.c (ffffffff813d0f24)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
```
In lib/decompress_unlzo.c (ffffffff81f9dc04)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81526e0b)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff815a64c0)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/sd.c (ffffffff815be0b4)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f66a6)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb5822)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/ipv4/tcp_input.c (ffffffff8176c7b2)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ae2cf)
Location: include/uapi/linux/swab.h:154
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
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
In kernel/bpf/core.c (ffffffff811803a8)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff81339463)
Location: include/uapi/linux/swab.h:160
Inline: True
```
```
In block/partitions/ldm.c (ffffffff81416991)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In lib/decompress_unlzo.c (ffffffff81fc9041)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579d5b)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff815fe750)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81606704)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff816177ec)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656826)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fe28e3)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/ipv4/tcp_input.c (ffffffff817d9d3d)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181b27e)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
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
In kernel/bpf/core.c (ffffffff8118c218)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f203)
Location: include/uapi/linux/swab.h:160
Inline: True
```
```
In block/partitions/ldm.c (ffffffff81431ec1)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In lib/decompress_unlzo.c (ffffffff82005f9a)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a629d)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8162dd88)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81635c24)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff816472b6)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684506)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817005e6)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff820206b2)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/ipv4/tcp_input.c (ffffffff81808356)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184cb47)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
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
In kernel/bpf/core.c (ffffffff8118feb7)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff81363cb0)
Location: include/uapi/linux/swab.h:160
Inline: True
```
```
In block/partitions/ldm.c (ffffffff8143ee64)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba75d)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff816431a4)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164ae84)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff8165becd)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff8166ffc9)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699919)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81715e0b)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff821035f8)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/ipv4/tcp_input.c (ffffffff8182872f)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81870594)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82111073)
Location: include/uapi/linux/swab.h:160
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff81388a20)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff8146b259)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620dfd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff816ac1b4)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b41c8)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff816c554a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff816d95c9)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817040b9)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8178700b)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8270ccd9)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/ipv4/tcp_input.c (ffffffff818a7b4f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0f94)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff8271b479)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff813b787f)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff8149ec41)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165abbd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff816e86dc)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f0258)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff817016ed)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff81715a75)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742840)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c812e)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82736f9b)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff818b1443)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff818fcef8)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819478df)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82745c97)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff813d0d8f)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff814b8fe9)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678b3d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8170c1dc)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81713ab8)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff81724635)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff817380b5)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817670c0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef7cf)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0ec7)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff818d5f9d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff8192b068)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819794af)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff828fffcf)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff813fb8be)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff814e7cb9)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816aefab)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8174790c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174f333)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/sd.c (ffffffff8175f82c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff81774095)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a488f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183022a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c51c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff8192378d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff8198e18a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2efd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff8291cbc8)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff8141579e)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff81501089)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d1c9b)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8176ba5c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81773513)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff8177bf48)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8178375d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff81798005)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c898f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861b5a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915eed)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff819559bd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff819c4dba)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19eed)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82926a4a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff81464008)
Location: include/uapi/linux/swab.h:171
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a33e7)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff815617b4)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In lib/decompress_unlzo.c (ffffffff82d0c810)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/base/regmap/regmap.c (ffffffff817da4a5)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
```
```
In drivers/scsi/scsi.c (ffffffff8182dd2c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81835877)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f2e9)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff818431ef)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sr.c (ffffffff8184a443)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
```
```
In drivers/ata/libata-scsi.c (ffffffff8185cb95)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892695)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81934b84)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:show_calibration_count
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27de2)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff81a285ad)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff81ab03cf)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_mss_option
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b59a)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
```
```
In net/mptcp/options.c (ffffffff81bb055a)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff8147f7cb)
Location: include/uapi/linux/swab.h:171
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0b8c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff8157d2a4)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In lib/decompress_unlzo.c (ffffffff82ff9de4)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef255)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
```
```
In drivers/scsi/scsi.c (ffffffff8183ed6c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184632e)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184f949)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81852c9c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sr.c (ffffffff8185a943)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
```
```
In drivers/ata/libata-scsi.c (ffffffff8186bc65)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a0685)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193bbf4)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:show_calibration_count
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info
```
```
In drivers/firmware/dmi_scan.c (ffffffff830164fa)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff81a28ecd)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff81abb4fc)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_mss_option
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19914)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
```
```
In net/mptcp/options.c (ffffffff81bc3d24)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff81485029)
Location: include/uapi/linux/swab.h:171
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c7163)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff81584dd7)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/decompress_unlzo.c (ffffffff832049fc)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3af5)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
```
```
In drivers/scsi/scsi.c (ffffffff81821f7c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff818295be)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832bdf)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8183660c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sr.c (ffffffff8183d7a9)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
```
```
In drivers/ata/libata-scsi.c (ffffffff8184ec15)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882db5)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f0d4)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:show_calibration_count
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info_ekth
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_ts_info_ekth
```
```
In drivers/firmware/dmi_scan.c (ffffffff832214a3)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff81a101c6)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff81aa64ac)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0738c)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/mptcp/options.c (ffffffff81bb4328)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151fc43)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b333e)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165dfce)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b25633)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696912)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b757ae)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2f92)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc9625)
Location: include/uapi/linux/swab.h:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In fs/ecryptfs/crypto.c (ffff8000104f8734)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffff800010603450)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bc6a0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffff80001096d9c0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffff800010975388)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffff800010981f9c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffff800010989f58)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/ata/libata-scsi.c (ffff8000109a1f60)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02de0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a4108)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/of/property.c (ffff800010b6e770)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
```
```
In net/core/filter.c (ffff800010bf7720)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffff800010c77764)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5e08)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffff8000114b7c6c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In drivers/char/tpm/tpm2-cmd.c (c09b5a04)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/of/property.c (c0c51600)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
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
In arch/powerpc/platforms/pseries/vphn.c (c0000000001036f0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vphn.c:vphn_unpack_associativity
```
```
In fs/ecryptfs/crypto.c (c000000000637fc4)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (c00000000079ea90)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095e134)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (c000000000a26cc4)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (c000000000a31360)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (c000000000a3e530)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (c000000000a4a520)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (c000000000a675d0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8ca0)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/of/property.c (c000000000c49370)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
```
```
In net/core/filter.c (c000000000cdd544)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (c000000000d7fe58)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (c000000000df5870)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (c0000000013ca89c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056e3fe)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071ad80)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In drivers/of/property.c (ffffffe000722f3a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
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
In fs/ecryptfs/crypto.c (ffffffff8140dd7e)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff814f9669)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816976eb)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8172014c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81727c03)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff81730638)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81737e4d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff8175d115)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d46f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb441)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff818f598d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff81964c2a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b957d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff8290b74e)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff813fe7fe)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff814e9b79)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816750db)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff816f957c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701033)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff81709a58)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81719aed)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff8173cfb5)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177623f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2cdd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff818af7bd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff8191e71a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197636d)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82903a9c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff8140b0fe)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff814f56f9)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c595b)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8175ef1c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff817669d3)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff8176f408)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff817785dd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ce85)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bd80f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855cea)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82910522)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff819469bd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff819cf3fa)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23ffd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82921098)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
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
In fs/ecryptfs/crypto.c (ffffffff81420d9e)
Location: include/uapi/linux/swab.h:161
Inline: True
```
```
In block/partitions/ldm.c (ffffffff8150e759)
Location: include/uapi/linux/swab.h:161
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dfe7b)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi.c (ffffffff8177a57c)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffffffff817820be)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffffffff8178aba8)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff817923fd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/ata/libata-scsi.c (ffffffff817a6cd5)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d803f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870e1a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82916f4f)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/filter.c (ffffffff819682cd)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/ipv4/tcp_input.c (ffffffff819d8f8a)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f442)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In lib/decompress_unlzo.c (ffffffff82927abc)
Location: include/uapi/linux/swab.h:161
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
</details>
</li>
</ul>

## Differences
