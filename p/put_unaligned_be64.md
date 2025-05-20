# Function: <code>put_unaligned_be64</code>

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
In fs/ecryptfs/mmap.c (ffffffff81304509)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff813a88f3)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In drivers/scsi/scsi_common.c (ffffffff815b15f0)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815bef86)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff815d1325)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff813385d9)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff813e5da1)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff816097f9)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81613ca6)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8162c131)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff8134e399)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff813fedc1)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff816390d9)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81643606)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/scsi/sd_zbc.c (ffffffff816487dd)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff8165d281)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff81362f19)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff8140c0da)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8164dcfa)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81657d26)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d109)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81671ecd)
Location: include/linux/unaligned/access_ok.h:62
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff81387bb9)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff81434afa)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff816b6fca)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816c11e6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6769)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff816db50d)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff813b68bc)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff81467653)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff816f3301)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816fd8cf)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702d57)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81717866)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff813cfe0c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814852c3)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8171ec61)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8172049f)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725723)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81739eb6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff813fa9fc)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814b3577)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8175a34e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8175bb1b)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760d83)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81775ecb)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff814148cc)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814cc2e7)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8177e25e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8177fa2b)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784d64)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81799e36)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff81462496)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In crypto/sha512_generic.c (ffffffff8152b72d)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff817da3b5)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff818418ee)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818440a7)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849460)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c371)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff81bb16fe)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff81bb1e9c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffffffff8147dde6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In crypto/sha512_generic.c (ffffffff815486fd)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef165)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81851e0e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818542f0)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8185971f)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b461)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff81bc563e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff81bc6249)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffffffff814841cc)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff81550dc9)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3a05)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81834e91)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81837d40)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c41f)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8184dd71)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff81bb60b8)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff81bb6da6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffffffff814db84c)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (ffffffff815b1da3)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff8185edee)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff818c1221)
Location: include/asm-generic/unaligned.h:80
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818c5097)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8d4c)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff818db3e1)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff81c850fd)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff81c85ddc)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffffffff8156941c)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (ffffffff8165a8d3)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff819a678e)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81a0d868)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81a11cb9)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a162a4)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2e3e0)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff81e2af00)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff81e2c123)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffffffff8160cfbc)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (ffffffff81714b9f)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1901e)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81b8d748)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81b91f84)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97074)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf630)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff820030b0)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff82004383)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e0bd9)
Location: include/asm-generic/unaligned.h:80
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81644e6f)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (ffffffff8174fad3)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/base/regmap/regmap.c (ffffffff81b67d0e)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/scsi/scsi_common.c (ffffffff81be1898)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81be845e)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed614)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0631f)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff8207f240)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff82080593)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e9459)
Location: include/asm-generic/unaligned.h:80
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e37f)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (ffffffff81791723)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff81c368c8)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81c3d9cb)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42d11)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5b0cf)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b9
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/mptcp/options.c (ffffffff82154730)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In net/mptcp/crypto.c (ffffffff82155a83)
Location: include/asm-generic/unaligned.h:80
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In fs/ecryptfs/mmap.c (ffff8000104f601c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffff8000105c81d0)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In drivers/scsi/scsi_common.c (ffff800010984908)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffff80001098ab60)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b938)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
```
```
In drivers/ata/libata-scsi.c (ffff8000109a4338)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (c06b38bc)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
```
```
In crypto/sha512_generic.c (c07757ec)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In drivers/scsi/scsi_common.c (c0a56ef8)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
```
```
In drivers/scsi/sd.c (c0a588fc)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (c0a5dcd0)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c0a72d84)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
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
In fs/ecryptfs/mmap.c (c000000000636e68)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In crypto/sha512_generic.c (c000000000751f84)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (c000000000a41788)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (c000000000a45aac)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c668)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c000000000a69810)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffe000364de6)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
```
```
In crypto/sha512_generic.c (ffffffe00040c230)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In drivers/scsi/scsi_common.c (ffffffe0005e9558)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005eab5e)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005effc0)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/be_byteshift.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
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
In fs/ecryptfs/mmap.c (ffffffff8140ceac)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814c48c7)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8173294e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8173411b)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739454)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8175ef26)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff813fd92c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814b52e7)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8170bd6e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81715dbb)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b0f4)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8173edb5)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff8140a22c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814c0957)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8177171e)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817748ab)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779be4)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ecb6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
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
In fs/ecryptfs/mmap.c (ffffffff8141ff1c)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In crypto/sha512_generic.c (ffffffff814d9427)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In drivers/scsi/scsi_common.c (ffffffff8178cebe)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8178e68b)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793a14)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8de6)
Location: include/linux/unaligned/access_ok.h:63
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
</details>
</li>
</ul>

## Differences
