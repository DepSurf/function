# Function: <code>intel_pmic_install_opregion_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f2840)
Location: drivers/acpi/pmic/intel_pmic.c:251
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff816f2840-ffffffff816f29b5: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8170fa70)
Location: drivers/acpi/pmic/intel_pmic.c:251
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff8170fa70-ffffffff8170fbe5: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f1340)
Location: drivers/acpi/pmic/intel_pmic.c:251
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff816f1340-ffffffff816f14b5: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8176b440)
Location: drivers/acpi/pmic/intel_pmic.c:256
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff8176b440-ffffffff8176b5b5: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, const struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff818a00e0)
Location: drivers/acpi/pmic/intel_pmic.c:256
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff818a00e0-ffffffff818a025e: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, const struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff819e9530)
Location: drivers/acpi/pmic/intel_pmic.c:256
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff819e9530-ffffffff819e96ae: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, const struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a31c50)
Location: drivers/acpi/pmic/intel_pmic.c:256
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff81a31c50-ffffffff81a31dce: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pmic_install_opregion_handler(struct device *dev, acpi_handle handle, struct regmap *regmap, const struct intel_pmic_opregion_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a7d0c0)
Location: drivers/acpi/pmic/intel_pmic.c:256
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
**Symbols:**

```
ffffffff81a7d0c0-ffffffff81a7d23e: intel_pmic_install_opregion_handler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct intel_pmic_opregion_data *d</code> ➡️ <code>const struct intel_pmic_opregion_data *d</code>
</li>
</ul>
</details>
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
