# Function: <code>ata_read_log_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d51a0)
Location: drivers/ata/libata-eh.c:1505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff815d51a0-ffffffff815d5367: ata_read_log_page.part.11 (STB_LOCAL)
ffffffff815d61e0-ffffffff815d620a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162ff0a)
Location: drivers/ata/libata-eh.c:1505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8162ec10-ffffffff8162edd7: ata_read_log_page.part.11 (STB_LOCAL)
ffffffff8162fc40-ffffffff8162fc6a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8166105a)
Location: drivers/ata/libata-eh.c:1505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8165fd60-ffffffff8165ff27: ata_read_log_page.part.11 (STB_LOCAL)
ffffffff81660d90-ffffffff81660dba: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166b559)
Location: drivers/ata/libata-core.c:2066
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81669680-ffffffff81669837: ata_read_log_page.part.38 (STB_LOCAL)
ffffffff81669840-ffffffff8166986a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d4bac)
Location: drivers/ata/libata-core.c:2067
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff816d2cd0-ffffffff816d2e87: ata_read_log_page.part.36 (STB_LOCAL)
ffffffff816d2e90-ffffffff816d2eba: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81710d83)
Location: drivers/ata/libata-core.c:2058
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8170f330-ffffffff8170f4bc: ata_read_log_page.part.32 (STB_LOCAL)
ffffffff817131f8-ffffffff8171321a: ata_read_log_page.part.32.cold.54 (STB_LOCAL)
ffffffff8170f4c0-ffffffff8170f4ea: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81733230)
Location: drivers/ata/libata-core.c:2058
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff817317e0-ffffffff8173196c: ata_read_log_page.part.33 (STB_LOCAL)
ffffffff817356a8-ffffffff817356ca: ata_read_log_page.part.33.cold.55 (STB_LOCAL)
ffffffff81731970-ffffffff8173199a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8176e45d)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8176cfa0-ffffffff8176d122: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff8177111d-ffffffff8177115e: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff8176d130-ffffffff8176d15a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817924cd)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81791010-ffffffff81791192: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff817950f8-ffffffff81795139: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff817911a0-ffffffff817911ca: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8185786e)
Location: drivers/ata/libata-core.c:1988
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_read_log_10h
```
**Symbols:**

```
ffffffff81855fa0-ffffffff81856175: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff818595d7-ffffffff8185960c: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff81856180-ffffffff818561aa: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81867aee)
Location: drivers/ata/libata-core.c:1988
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_read_log_10h
```
**Symbols:**

```
ffffffff81866220-ffffffff818663f5: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff81c175ea-ffffffff81c1761f: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff81866400-ffffffff8186642a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1988
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81c09191-ffffffff81c091ca: ata_read_log_page.cold (STB_LOCAL)
ffffffff81848960-ffffffff81848b4a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1991
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81d0da98-ffffffff81d0dac8: ata_read_log_page.cold (STB_LOCAL)
ffffffff818d5930-ffffffff818d5afb: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1962
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81ed6aba-ffffffff81ed6af7: ata_read_log_page.cold (STB_LOCAL)
ffffffff81a26350-ffffffff81a265ad: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba8570)
Location: drivers/ata/libata-core.c:1962
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81ba8570-ffffffff81ba882e: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bff210)
Location: drivers/ata/libata-core.c:1996
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81bff210-ffffffff81bff4ce: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c55260)
Location: drivers/ata/libata-core.c:2131
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81c55260-ffffffff81c5551e: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099c7cc)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffff80001099ad28-ffff80001099aef0: ata_read_log_page.part.0 (STB_LOCAL)
ffff80001099aef0-ffff80001099af74: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (c0a6c9b0)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
c0a6af58-c0a6b140: ata_read_log_page.part.0 (STB_LOCAL)
c0a6b140-c0a6b184: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a604e0)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
c000000000a5e300-c000000000a5e540: ata_read_log_page.part.0 (STB_LOCAL)
c000000000a5e540-c000000000a5e578: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fcbe6)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffe0005fb48e-ffffffe0005fb616: ata_read_log_page.part.0 (STB_LOCAL)
ffffffe0005fb616-ffffffe0005fb670: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8175760d)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81756150-ffffffff817562d2: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff8175a208-ffffffff8175a249: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff817562e0-ffffffff8175630a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817374ad)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81735ff0-ffffffff81736172: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff8173a0a8-ffffffff8173a0e9: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff81736180-ffffffff817361aa: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178734d)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81785e90-ffffffff81786012: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff81789f78-ffffffff81789fb9: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff81786020-ffffffff8178604a: ata_read_log_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_read_log_page(struct ata_device *dev, u8 log, u8 page, void *buf, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a119d)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_log_supported
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8179fce0-ffffffff8179fe62: ata_read_log_page.part.0 (STB_LOCAL)
ffffffff817a3dc8-ffffffff817a3e09: ata_read_log_page.part.0.cold (STB_LOCAL)
ffffffff8179fe70-ffffffff8179fe9a: ata_read_log_page (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
