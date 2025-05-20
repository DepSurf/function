# Function: <code>put_unaligned_be16</code>

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
In fs/ecryptfs/crypto.c (ffffffff8130648e)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
```
```
In drivers/scsi/sd.c (ffffffff815bf258)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff815d12df)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f5e00)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff8133a997)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8160987f)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81614ef2)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8162a6df)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81655ba7)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff81350734)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8163915f)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81644a7e)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8165b95f)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81683887)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff81365239)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8164dd74)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8165a7d7)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8166f9dd)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81698cb6)
Location: include/linux/unaligned/access_ok.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff81389f09)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff816b7044)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816c399d)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff816d8fbd)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81703bbc)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff813b8d61)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff816f337b)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816ffaeb)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff817179ff)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817444b5)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff813d22d1)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8171ecdb)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8172303f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8173a04f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817685b2)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff813fcd30)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8175a3e8)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8176051c)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff81773a1f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a6c14)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff81416c10)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8177e2f8)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817843f4)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8179798f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817ca674)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff81463ec6)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
```
In drivers/base/regmap/regmap.c (ffffffff817da465)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_common.c (ffffffff8184171c)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81843f7d)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff81849b38)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8185b282)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81894b08)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff8147f686)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef215)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81851c3c)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81854228)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff8185a090)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8186a382)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3232)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff81bc5911)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff814862f7)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3ab5)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81834cbf)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81837c77)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff8183d09a)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8184cc32)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81884f55)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff81bb64bb)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff814dda87)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff8185eec0)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b58a9)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_common.c (ffffffff818c104f)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff818c504a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff818c9a34)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff818da452)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81916921)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff81c8542c)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff8156bb56)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff819a6850)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a00dc8)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_common.c (ffffffff81a0d90a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81a11cab)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff81a16d84)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2ae54)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a68cc5)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff81e2af2e)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff8160fb86)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19120)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7f228)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_common.c (ffffffff81b8d7fa)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81b91f76)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff81b97be4)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81bad774)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfb65a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff820030de)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff81647a16)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff81b67e10)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi.c (ffffffff81bc8a0a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd31db)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_common.c (ffffffff81be194a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81be8450)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff81bee163)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c086a7)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c60bee)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff8207f26e)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffffffff81680ec6)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbbb60)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/scsi/scsi.c (ffffffff81c1d8fa)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27e5b)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_common.c (ffffffff81c3697a)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
  - drivers/scsi/scsi_common.c:scsi_set_sense_field_pointer
```
```
In drivers/scsi/sd.c (ffffffff81c3d9bd)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sr.c (ffffffff81c43870)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5d787)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_msense_control_spgt2
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d175be)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/mptcp/options.c (ffffffff8215475e)
Location: include/asm-generic/unaligned.h:70
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In fs/ecryptfs/crypto.c (ffff8000104f81d0)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
```
```
In drivers/scsi/scsi_common.c (ffff8000109849d4)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffff80001098acf8)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffff80001099fcec)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02320)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (c06b5bb0)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (c0a56f84)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
```
```
In drivers/scsi/sd.c (c0a5cdc0)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (c0a739ec)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adc570)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (c00000000063a14c)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (c000000000a41868)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (c000000000a4b548)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (c000000000a66ac0)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaad60)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffe000366c7a)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffe0005e9676)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005ef0c4)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffe000602302)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062ed6e)
Location: include/linux/unaligned/be_byteshift.h:56
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff8140f1f0)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff817329e8)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81738ae4)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8175ca9f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178f154)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff813ffc70)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8170be08)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8171a784)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c93f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81777f24)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff8140c570)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff817717b8)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81779274)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c80f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bf4f4)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
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
In fs/ecryptfs/crypto.c (ffffffff814221f0)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In drivers/scsi/scsi_common.c (ffffffff8178cf58)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81793094)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/ata/libata-scsi.c (ffffffff817a665f)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d9784)
Location: include/linux/unaligned/access_ok.h:53
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
</details>
</li>
</ul>

## Differences
