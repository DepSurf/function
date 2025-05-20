# Function: <code>twl_i2c_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff815877a0)
Location: drivers/mfd/twl-core.c:454
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
**Symbols:**

```
ffffffff815877a0-ffffffff81587830: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff815dc800)
Location: drivers/mfd/twl-core.c:454
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff815dc800-ffffffff815dc88f: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff816094d0)
Location: drivers/mfd/twl-core.c:453
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff816094d0-ffffffff8160955f: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8161d4b0)
Location: drivers/mfd/twl-core.c:453
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff8161d4b0-ffffffff8161d53f: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81685cf0)
Location: drivers/mfd/twl-core.c:453
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81685cf0-ffffffff81685d7f: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:453
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff816c2435-ffffffff816c2455: twl_i2c_write.cold.6 (STB_LOCAL)
ffffffff816c1de0-ffffffff816c1e56: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:453
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff816e402e-ffffffff816e404e: twl_i2c_write.cold.6 (STB_LOCAL)
ffffffff816e3220-ffffffff816e3296: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff8171d633-ffffffff8171d653: twl_i2c_write.cold (STB_LOCAL)
ffffffff8171c8c0-ffffffff8171c934: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81741906-ffffffff81741926: twl_i2c_write.cold (STB_LOCAL)
ffffffff81740b90-ffffffff81740c04: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff817ff415-ffffffff817ff436: twl_i2c_write.cold (STB_LOCAL)
ffffffff817fe360-ffffffff817fe3d7: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81c13020-ffffffff81c13041: twl_i2c_write.cold (STB_LOCAL)
ffffffff8180f790-ffffffff8180f807: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81c05177-ffffffff81c05198: twl_i2c_write.cold (STB_LOCAL)
ffffffff817f3fc0-ffffffff817f4037: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81d084c0-ffffffff81d084e1: twl_i2c_write.cold (STB_LOCAL)
ffffffff8187d2f0-ffffffff8187d367: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81ed0956-ffffffff81ed0977: twl_i2c_write.cold (STB_LOCAL)
ffffffff819c5750-ffffffff819c57d3: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b3c660)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81b3c660-ffffffff81b3c71b: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b8fa80)
Location: drivers/mfd/twl-core.c:443
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81b8fa80-ffffffff81b8fb3b: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81be39a0)
Location: drivers/mfd/twl-core.c:445
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81be39a0-ffffffff81be3a5b: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffff80001093c378)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffff80001093c378-ffff80001093c418: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0a253a4)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/gpio/gpio-twl4030.c:twl_set
  - drivers/gpio/gpio-twl4030.c:twl_free
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl4030_set_gpio_direction
  - drivers/regulator/twl-regulator.c:twlreg_probe
  - drivers/regulator/twl-regulator.c:twl4030smps_set_voltage
  - drivers/regulator/twl-regulator.c:twl4030ldo_set_voltage_sel
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030reg_disable
  - drivers/regulator/twl-regulator.c:twl4030reg_enable
  - drivers/regulator/twl6030-regulator.c:twl6030smps_set_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030ldo_set_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030reg_set_mode
  - drivers/regulator/twl6030-regulator.c:twl6030reg_disable
  - drivers/regulator/twl6030-regulator.c:twl6030reg_enable
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
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
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_write_u8
```
**Symbols:**

```
c0a253a4-c0a25440: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0000000009e3dd0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
c0000000009e3dd0-c0000000009e3ea4: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffe0005b082a)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffe0005b082a-ffffffe0005b08be: twl_i2c_write (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81734dc6-ffffffff81734de6: twl_i2c_write.cold (STB_LOCAL)
ffffffff81734050-ffffffff817340c4: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int twl_i2c_write(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:440
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81750206-ffffffff81750226: twl_i2c_write.cold (STB_LOCAL)
ffffffff8174f490-ffffffff8174f504: twl_i2c_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
