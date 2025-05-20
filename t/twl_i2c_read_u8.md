# Function: <code>twl_i2c_read_u8</code>

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
In drivers/mfd/twl-core.c (ffffffff815878c6)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588716)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81588fa6)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815892e8)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
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
In drivers/mfd/twl-core.c (ffffffff815dcf75)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd796)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff815de147)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815de531)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81609c45)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a426)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8160add7)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8160b1c1)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff8161df3b)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e526)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8161ef07)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8161f2f1)
Location: include/linux/i2c/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81686781)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686d66)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81687747)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81687b31)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff816c2788)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2ed0)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff816c38ab)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816c3ca8)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff816e38b0)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e42c0)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff816e4c9b)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816e5098)
Location: include/linux/mfd/twl.h:193
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff8171d520)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171d950)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8171e34b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8171e793)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff817417f3)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741c20)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8174261b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81742a63)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff817ff30c)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff740)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8180017b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81800543)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff8181073c)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff818109e0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8181120b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81811543)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff817f4edc)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5160)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff817f597b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817f5cb3)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff8187df4c)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e210)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8187eb0b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8187ef04)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff819c62da)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c66e4)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff819c705b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff819c741f)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81b3cd17)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d1d4)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b3dd87)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b3e1f0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81b901fd)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90664)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b91217)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b91680)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81be4163)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be45d4)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81be51b7)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81be5620)
Location: include/linux/mfd/twl.h:181
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffff80001093d008)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d63c)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093df14)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffff80001093e9d8)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In arch/arm/mach-omap2/omap_twl.c (c033bb34)
Location: include/linux/mfd/twl.h:179
Inline: True
```
```
In drivers/gpio/gpio-twl4030.c (c087285c)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/gpio/gpio-twl4030.c:twl_get_direction
  - drivers/gpio/gpio-twl4030.c:twl_get
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl4030_set_gpio_direction
```
```
In drivers/regulator/twl-regulator.c (c0956fc8)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/regulator/twl-regulator.c:twl4030smps_get_voltage
  - drivers/regulator/twl-regulator.c:twl4030ldo_get_voltage_sel
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030_wait_pb_ready
  - drivers/regulator/twl-regulator.c:twlreg_grp
```
```
In drivers/regulator/twl6030-regulator.c (c09581f0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twl6030smps_get_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030ldo_get_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030reg_get_status
  - drivers/regulator/twl6030-regulator.c:twl6030reg_is_enabled
  - drivers/regulator/twl6030-regulator.c:twlreg_grp
```
```
In drivers/mfd/twl-core.c (c0a25aa4)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (c0a26088)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (c0a269c8)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-power.c (c0a27878)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_probe
  - drivers/mfd/twl4030-power.c:twl4030_power_off
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
  - drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts
```
```
In drivers/mfd/twl4030-audio.c (c0a28198)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
```
In drivers/rtc/rtc-twl.c (c0b8f4a4)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_interrupt
  - drivers/rtc/rtc-twl.c:twl_rtc_read_u8
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
In drivers/mfd/twl-core.c (c0000000009e4cd0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5528)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e62ac)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (c0000000009e7000)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffe0005b117a)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b15f2)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b1ff0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffe0005b2832)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff81734cb3)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817350e0)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81735adb)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81735f23)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
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
In drivers/mfd/twl-core.c (ffffffff817500f3)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750520)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81750f1b)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81751363)
Location: include/linux/mfd/twl.h:179
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
</details>
</li>
</ul>

## Differences
