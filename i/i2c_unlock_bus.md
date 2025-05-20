# Function: <code>i2c_unlock_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff815d051a)
Location: include/linux/i2c.h:610
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core.c (ffffffff816da690)
Location: include/linux/i2c.h:610
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_slave_register
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_transfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff815fd127)
Location: include/linux/i2c.h:646
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core.c (ffffffff8170bf3e)
Location: include/linux/i2c.h:646
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_transfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81610ec7)
Location: include/linux/i2c.h:661
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720873)
Location: include/linux/i2c.h:661
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81722f3c)
Location: include/linux/i2c.h:661
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8167974d)
Location: include/linux/i2c.h:663
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81791bb1)
Location: include/linux/i2c.h:663
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794348)
Location: include/linux/i2c.h:663
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff816b51fd)
Location: include/linux/i2c.h:752
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d45d5)
Location: include/linux/i2c.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6ec6)
Location: include/linux/i2c.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff816d645d)
Location: include/linux/i2c.h:760
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb755)
Location: include/linux/i2c.h:760
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe244)
Location: include/linux/i2c.h:760
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81711c2d)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c546)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f428)
Location: include/linux/i2c.h:779
Inline: True
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81735f2d)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186df46)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870dc8)
Location: include/linux/i2c.h:779
Inline: True
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
In drivers/mfd/88pm860x-i2c.c (ffffffff817f352d)
Location: include/linux/i2c.h:781
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941fbd)
Location: include/linux/i2c.h:781
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944dfc)
Location: include/linux/i2c.h:781
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8180718d)
Location: include/linux/i2c.h:789
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194830d)
Location: include/linux/i2c.h:789
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ae3c)
Location: include/linux/i2c.h:789
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
In drivers/mfd/88pm860x-i2c.c (ffffffff817ebdbd)
Location: include/linux/i2c.h:797
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bc6d)
Location: include/linux/i2c.h:797
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e97c)
Location: include/linux/i2c.h:797
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8187893d)
Location: include/linux/i2c.h:806
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cee2d)
Location: include/linux/i2c.h:806
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1bac)
Location: include/linux/i2c.h:806
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
In drivers/mfd/88pm860x-i2c.c (ffffffff819c0dad)
Location: include/linux/i2c.h:815
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30be2)
Location: include/linux/i2c.h:815
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34188)
Location: include/linux/i2c.h:815
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39afb)
Location: include/linux/i2c.h:815
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81b371ed)
Location: include/linux/i2c.h:817
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5512)
Location: include/linux/i2c.h:817
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc917b)
Location: include/linux/i2c.h:817
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf48b)
Location: include/linux/i2c.h:817
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81b8a66d)
Location: include/linux/i2c.h:823
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d1a2)
Location: include/linux/i2c.h:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30e9b)
Location: include/linux/i2c.h:823
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d3755b)
Location: include/linux/i2c.h:823
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81bde56d)
Location: include/linux/i2c.h:816
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de304b)
Location: include/linux/i2c.h:816
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6ecb)
Location: include/linux/i2c.h:816
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded7db)
Location: include/linux/i2c.h:816
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
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
In drivers/mfd/88pm860x-i2c.c (ffff80001092d79c)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab181c)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab49b8)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-slave.c (ffff800010ab64e0)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_unregister
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc9dc)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_resume_noirq
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_suspend_noirq
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
In drivers/mfd/88pm860x-i2c.c (c0a0c17c)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (c0b928e4)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b95bf0)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-slave.c (c0b967cc)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_unregister
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e154)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_resume_noirq
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_suspend_noirq
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
In drivers/char/tpm/tpm_i2c_infineon.c (c00000000096628c)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
```
```
In drivers/mfd/88pm860x-i2c.c (c0000000009ccee0)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (c000000000b94774)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98bbc)
Location: include/linux/i2c.h:779
Inline: True
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
In drivers/mfd/88pm860x-i2c.c (ffffffe0005a471c)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b92ae)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbe90)
Location: include/linux/i2c.h:779
Inline: True
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
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff817293ed)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff818620d6)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864f58)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868a22)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_remove
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8174482d)
Location: include/linux/i2c.h:779
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d336)
Location: include/linux/i2c.h:779
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880208)
Location: include/linux/i2c.h:779
Inline: True
```
</details>
</li>
</ul>

## Differences
