# Function: <code>i2c_lock_bus</code>

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
In drivers/mfd/88pm860x-i2c.c (ffffffff815d0460)
Location: include/linux/i2c.h:598
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core.c (ffffffff816da666)
Location: include/linux/i2c.h:598
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
In drivers/mfd/88pm860x-i2c.c (ffffffff815fd074)
Location: include/linux/i2c.h:620
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core.c (ffffffff8170beba)
Location: include/linux/i2c.h:620
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81610e14)
Location: include/linux/i2c.h:635
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817208cc)
Location: include/linux/i2c.h:635
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81722ec6)
Location: include/linux/i2c.h:635
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
In drivers/mfd/88pm860x-i2c.c (ffffffff816796a7)
Location: include/linux/i2c.h:637
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81791c14)
Location: include/linux/i2c.h:637
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817942c6)
Location: include/linux/i2c.h:637
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
In drivers/mfd/88pm860x-i2c.c (ffffffff816b515c)
Location: include/linux/i2c.h:726
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d45f8)
Location: include/linux/i2c.h:726
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6e2a)
Location: include/linux/i2c.h:726
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
In drivers/mfd/88pm860x-i2c.c (ffffffff816d63bc)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb778)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe1e5)
Location: include/linux/i2c.h:734
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81711b8c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c518)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f3ec)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81735e8c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186df18)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870d8c)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (ffffffff817f348c)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941f8f)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944dc0)
Location: include/linux/i2c.h:755
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
In drivers/mfd/88pm860x-i2c.c (ffffffff818070ec)
Location: include/linux/i2c.h:763
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819482df)
Location: include/linux/i2c.h:763
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ae00)
Location: include/linux/i2c.h:763
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
In drivers/mfd/88pm860x-i2c.c (ffffffff817ebd1c)
Location: include/linux/i2c.h:771
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bc3f)
Location: include/linux/i2c.h:771
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e940)
Location: include/linux/i2c.h:771
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8187889c)
Location: include/linux/i2c.h:780
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cedff)
Location: include/linux/i2c.h:780
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1b70)
Location: include/linux/i2c.h:780
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
In drivers/mfd/88pm860x-i2c.c (ffffffff819c0d0c)
Location: include/linux/i2c.h:789
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30bb5)
Location: include/linux/i2c.h:789
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b3414c)
Location: include/linux/i2c.h:789
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39adc)
Location: include/linux/i2c.h:789
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81b3714c)
Location: include/linux/i2c.h:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc54e5)
Location: include/linux/i2c.h:791
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc913d)
Location: include/linux/i2c.h:791
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf46c)
Location: include/linux/i2c.h:791
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81b8a5cc)
Location: include/linux/i2c.h:797
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d175)
Location: include/linux/i2c.h:797
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30e5d)
Location: include/linux/i2c.h:797
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d3753c)
Location: include/linux/i2c.h:797
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
In drivers/mfd/88pm860x-i2c.c (ffffffff81bde4cc)
Location: include/linux/i2c.h:790
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de301e)
Location: include/linux/i2c.h:790
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6e8d)
Location: include/linux/i2c.h:790
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded7bc)
Location: include/linux/i2c.h:790
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
In drivers/mfd/88pm860x-i2c.c (ffff80001092d6f4)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab17f0)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab497c)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-slave.c (ffff800010ab64b8)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_unregister
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc9a8)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (c0a0c0f0)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (c0b928ac)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b95ba0)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-slave.c (c0b967a4)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_unregister
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e134)
Location: include/linux/i2c.h:753
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
In drivers/char/tpm/tpm_i2c_infineon.c (c0000000009661d0)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
```
```
In drivers/mfd/88pm860x-i2c.c (c0000000009cce4c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (c000000000b94730)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98b68)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (ffffffe0005a469c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9296)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbe70)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8172934c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff818620a8)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864f1c)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff818689e0)
Location: include/linux/i2c.h:753
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
In drivers/mfd/88pm860x-i2c.c (ffffffff8174478c)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d308)
Location: include/linux/i2c.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818801cc)
Location: include/linux/i2c.h:753
Inline: True
```
</details>
</li>
</ul>

## Differences
