# Function: <code>twl_i2c_write_u8</code>

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
In drivers/mfd/twl-core.c (ffffffff81587cfa)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588c79)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81588fdf)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81589342)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
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
In drivers/mfd/twl-core.c (ffffffff815dcf91)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815ddcdd)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff815de203)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815de6d7)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81609c61)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a96d)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8160ae93)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8160b367)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8161df57)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161ec32)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8161efc3)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8161f496)
Location: include/linux/i2c/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8168679d)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81687472)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81687803)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81687cd6)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff816c27c0)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c338a)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff816c3972)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816c3e53)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff816e38e8)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e477a)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff816e4d62)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816e5243)
Location: include/linux/mfd/twl.h:189
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8171d558)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171de06)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8171e413)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8171e89b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8174182b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817420d6)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff817426e3)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81742b6b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff817ff344)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl-core.c:twl_read_idcode_register
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffa10)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8180021a)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8180064b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81810774)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl-core.c:twl_read_idcode_register
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81810cb0)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff818112aa)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8181164b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff817f4f14)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5430)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff817f5a1a)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817f5dbb)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8187df84)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e5a5)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8187ebaa)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8187f04b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff819c62ff)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6a85)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff819c7122)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff819c755b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81b3cd3c)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d5e8)
Location: include/linux/mfd/twl.h:175
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b3de82)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b3e425)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81b90222)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90a68)
Location: include/linux/mfd/twl.h:177
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b91312)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b918b5)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81be4188)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be49d8)
Location: include/linux/mfd/twl.h:177
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81be52b2)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81be5855)
Location: include/linux/mfd/twl.h:177
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffff80001093d040)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d9f0)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093dffc)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
```
```
In drivers/mfd/twl4030-audio.c (ffff80001093eb28)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/gpio/gpio-twl4030.c (c0873028)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/gpio/gpio-twl4030.c:twl_set
  - drivers/gpio/gpio-twl4030.c:twl_free
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl4030_set_gpio_direction
```
```
In drivers/regulator/twl-regulator.c (c09575f0)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/regulator/twl-regulator.c:twlreg_probe
  - drivers/regulator/twl-regulator.c:twl4030smps_set_voltage
  - drivers/regulator/twl-regulator.c:twl4030ldo_set_voltage_sel
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_disable
  - drivers/regulator/twl-regulator.c:twl4030reg_enable
```
```
In drivers/regulator/twl6030-regulator.c (c0958000)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/regulator/twl6030-regulator.c:twl6030smps_set_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030ldo_set_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030reg_set_mode
  - drivers/regulator/twl6030-regulator.c:twl6030reg_disable
  - drivers/regulator/twl6030-regulator.c:twl6030reg_enable
```
```
In drivers/mfd/twl-core.c (c0a25ad8)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (c0a2644c)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (c0a26ab4)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
```
```
In drivers/mfd/twl4030-power.c (c0a2777c)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
  - drivers/mfd/twl4030-power.c:twl4030_remove_script
```
```
In drivers/mfd/twl4030-audio.c (c0a282d4)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
```
In drivers/rtc/rtc-twl.c (c0b8f278)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_write_u8
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
In drivers/mfd/twl-core.c (c0000000009e4d04)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5a60)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e63b0)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
```
```
In drivers/mfd/twl4030-audio.c (c0000000009e71bc)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffe0005b1190)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1b6c)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b2082)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
```
```
In drivers/mfd/twl4030-audio.c (ffffffe0005b2950)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff81734ceb)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81735596)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81735ba3)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8173602b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
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
In drivers/mfd/twl-core.c (ffffffff8175012b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817509d6)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81750fe3)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8175146b)
Location: include/linux/mfd/twl.h:175
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
</details>
</li>
</ul>

## Differences
