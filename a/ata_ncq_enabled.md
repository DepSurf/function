# Function: <code>ata_ncq_enabled</code>

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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1629
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/libata.h:1629
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1629
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
In drivers/ata/libata-core.c (ffffffff81622c83)
Location: include/linux/libata.h:1606
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81629bfa)
Location: include/linux/libata.h:1606
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff81632358)
Location: include/linux/libata.h:1606
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff816537fe)
Location: include/linux/libata.h:1612
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8165a90a)
Location: include/linux/libata.h:1612
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff816634a8)
Location: include/linux/libata.h:1612
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff81667f64)
Location: include/linux/libata.h:1615
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8166ef1e)
Location: include/linux/libata.h:1615
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff81677d17)
Location: include/linux/libata.h:1615
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff816d15d4)
Location: include/linux/libata.h:1616
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff816d84fe)
Location: include/linux/libata.h:1616
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff816e135a)
Location: include/linux/libata.h:1616
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff8170de2a)
Location: include/linux/libata.h:1643
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81714e9f)
Location: include/linux/libata.h:1643
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff8171dbf0)
Location: include/linux/libata.h:1643
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff8173029a)
Location: include/linux/libata.h:1642
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8173745f)
Location: include/linux/libata.h:1642
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff817404d0)
Location: include/linux/libata.h:1642
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff8176ba00)
Location: include/linux/libata.h:1627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81772fe3)
Location: include/linux/libata.h:1627
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff8177c302)
Location: include/linux/libata.h:1627
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff8178fa70)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81796f43)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff8179fe82)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff818543bc)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c568)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff818649a2)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818680d0)
Location: include/linux/libata.h:1692
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
In drivers/ata/libata-core.c (ffffffff8186468c)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b64e)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff818737a2)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81876ee0)
Location: include/linux/libata.h:1692
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
In drivers/ata/libata-core.c (ffffffff8184712c)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8184df4c)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81855dc8)
Location: include/linux/libata.h:1692
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818596e6)
Location: include/linux/libata.h:1692
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
In drivers/ata/libata-core.c (ffffffff818d3e2c)
Location: include/linux/libata.h:1701
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff818db5bc)
Location: include/linux/libata.h:1701
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff818e43c7)
Location: include/linux/libata.h:1701
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818e8296)
Location: include/linux/libata.h:1701
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
In drivers/ata/libata-core.c (ffffffff81a2453c)
Location: include/linux/libata.h:1697
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2c1d5)
Location: include/linux/libata.h:1697
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81a35754)
Location: include/linux/libata.h:1697
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81a39d47)
Location: include/linux/libata.h:1697
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
In drivers/ata/libata-core.c (ffffffff81ba657e)
Location: include/linux/libata.h:1702
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf7c5)
Location: include/linux/libata.h:1702
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81bba254)
Location: include/linux/libata.h:1702
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf029)
Location: include/linux/libata.h:1702
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81bfd0f2)
Location: include/linux/libata.h:1738
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81c06e1b)
Location: include/linux/libata.h:1738
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81c11aed)
Location: include/linux/libata.h:1738
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff81c52df2)
Location: include/linux/libata.h:1739
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5befb)
Location: include/linux/libata.h:1739
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81c66ccd)
Location: include/linux/libata.h:1739
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffff800010999598)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffff8000109a20a0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffff8000109ab8ac)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (c0a69500)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (c0a72270)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (c0a7b194)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (c000000000a5c5f0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (c000000000a65e1c)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (c000000000a728a0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffe0005f9f52)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffe0006010bc)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffe000608f5a)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff81754be0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8175c053)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81764f72)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff81734a80)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8173bef3)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81744dd2)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff817848f0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff8178bdc3)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff81794d02)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-core.c (ffffffff8179e6e0)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_build_rw_tf
```
```
In drivers/ata/libata-scsi.c (ffffffff817a5c13)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/ata/libata-eh.c (ffffffff817aeb72)
Location: include/linux/libata.h:1629
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
</details>
</li>
</ul>

## Differences
