# Function: <code>twl_i2c_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81587830)
Location: drivers/mfd/twl-core.c:482
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
```
**Symbols:**

```
ffffffff81587830-ffffffff815878c0: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff815dc890)
Location: drivers/mfd/twl-core.c:482
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff815dc890-ffffffff815dc91f: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81609560)
Location: drivers/mfd/twl-core.c:481
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81609560-ffffffff816095ef: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8161d540)
Location: drivers/mfd/twl-core.c:481
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff8161d540-ffffffff8161d5cf: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81685d80)
Location: drivers/mfd/twl-core.c:481
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81685d80-ffffffff81685e0f: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:481
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff816c2455-ffffffff816c2475: twl_i2c_read.cold.7 (STB_LOCAL)
ffffffff816c1e60-ffffffff816c1ed6: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:481
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff816e404e-ffffffff816e406e: twl_i2c_read.cold.7 (STB_LOCAL)
ffffffff816e32a0-ffffffff816e3316: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff8171d653-ffffffff8171d673: twl_i2c_read.cold (STB_LOCAL)
ffffffff8171c940-ffffffff8171c9b4: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81741926-ffffffff81741946: twl_i2c_read.cold (STB_LOCAL)
ffffffff81740c10-ffffffff81740c84: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff817ff436-ffffffff817ff457: twl_i2c_read.cold (STB_LOCAL)
ffffffff817fe3e0-ffffffff817fe457: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl-core.c:twl_read_idcode_register
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81c13041-ffffffff81c13062: twl_i2c_read.cold (STB_LOCAL)
ffffffff8180f810-ffffffff8180f887: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81c05198-ffffffff81c051b9: twl_i2c_read.cold (STB_LOCAL)
ffffffff817f4040-ffffffff817f40b7: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81d084e1-ffffffff81d08502: twl_i2c_read.cold (STB_LOCAL)
ffffffff8187d370-ffffffff8187d3e7: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81ed0977-ffffffff81ed0998: twl_i2c_read.cold (STB_LOCAL)
ffffffff819c57e0-ffffffff819c5863: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b3c730)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81b3c730-ffffffff81b3c7eb: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b8fb50)
Location: drivers/mfd/twl-core.c:471
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81b8fb50-ffffffff81b8fc0b: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81be3a70)
Location: drivers/mfd/twl-core.c:473
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81be3a70-ffffffff81be3b2b: twl_i2c_read (STB_GLOBAL)
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
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffff80001093c418)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffff80001093c418-ffff80001093c4b8: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0a25440)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/gpio/gpio-twl4030.c:twl_get_direction
  - drivers/gpio/gpio-twl4030.c:twl_get
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-twl4030.c:twl4030_set_gpio_direction
  - drivers/regulator/twl-regulator.c:twl4030smps_get_voltage
  - drivers/regulator/twl-regulator.c:twl4030ldo_get_voltage_sel
  - drivers/regulator/twl-regulator.c:twl4030reg_set_mode
  - drivers/regulator/twl-regulator.c:twl4030_wait_pb_ready
  - drivers/regulator/twl-regulator.c:twlreg_grp
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
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
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
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
  - drivers/rtc/rtc-twl.c:twl_rtc_interrupt
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_u8
```
**Symbols:**

```
c0a25440-c0a254dc: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0000000009e3eb0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
c0000000009e3eb0-c0000000009e3f84: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffe0005b08be)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffe0005b08be-ffffffe0005b0952: twl_i2c_read (STB_GLOBAL)
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
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81734de6-ffffffff81734e06: twl_i2c_read.cold (STB_LOCAL)
ffffffff817340d0-ffffffff81734144: twl_i2c_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int twl_i2c_read(u8 mod_no, u8 *value, u8 reg, unsigned int num_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:468
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_get_hfclk_rate
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask
  - drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask
  - drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource
  - drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource
```
**Symbols:**

```
ffffffff81750226-ffffffff81750246: twl_i2c_read.cold (STB_LOCAL)
ffffffff8174f510-ffffffff8174f584: twl_i2c_read (STB_GLOBAL)
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
