# Function: <code>ata_identify_page_supported</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816698d0)
Location: drivers/ata/libata-core.c:2123
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff816698d0-ffffffff816699bd: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d2f20)
Location: drivers/ata/libata-core.c:2124
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff816d2f20-ffffffff816d300d: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2115
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8170f550-ffffffff8170f60b: ata_identify_page_supported (STB_LOCAL)
ffffffff8171321a-ffffffff8171325b: ata_identify_page_supported.cold.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2115
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81731a00-ffffffff81731ab2: ata_identify_page_supported (STB_LOCAL)
ffffffff817356ca-ffffffff8173570a: ata_identify_page_supported.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8176d1c0-ffffffff8176d26e: ata_identify_page_supported (STB_LOCAL)
ffffffff8177115e-ffffffff8177119e: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81791230-ffffffff817912de: ata_identify_page_supported (STB_LOCAL)
ffffffff81795139-ffffffff81795179: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2045
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
```
**Symbols:**

```
ffffffff818561b0-ffffffff81856294: ata_identify_page_supported (STB_LOCAL)
ffffffff8185960c-ffffffff81859629: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2045
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
```
**Symbols:**

```
ffffffff81866430-ffffffff81866514: ata_identify_page_supported (STB_LOCAL)
ffffffff81c1761f-ffffffff81c1763c: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2045
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81848b50-ffffffff81848c00: ata_identify_page_supported (STB_LOCAL)
ffffffff81c091ca-ffffffff81c09206: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2051
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff818d5b00-ffffffff818d5bae: ata_identify_page_supported (STB_LOCAL)
ffffffff81d0dac8-ffffffff81d0dae5: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2025
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81a266d0-ffffffff81a267da: ata_identify_page_supported (STB_LOCAL)
ffffffff81ed6b02-ffffffff81ed6b22: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba8ae0)
Location: drivers/ata/libata-core.c:2026
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81ba8ae0-ffffffff81ba8bfd: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bff610)
Location: drivers/ata/libata-core.c:2060
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
```
**Symbols:**

```
ffffffff81bff610-ffffffff81bff752: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c55660)
Location: drivers/ata/libata-core.c:2195
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_cdl
```
**Symbols:**

```
ffffffff81c55660-ffffffff81c557a2: ata_identify_page_supported (STB_LOCAL)
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
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099b000)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffff80001099b000-ffff80001099b114: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6b1f8)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c0a6b1f8-c0a6b2f4: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5e630)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c000000000a5e630-c000000000a5e78c: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fb6f4)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffe0005fb6f4-ffffffe0005fb7d8: ata_identify_page_supported (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81756370-ffffffff8175641e: ata_identify_page_supported (STB_LOCAL)
ffffffff8175a249-ffffffff8175a289: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81736210-ffffffff817362be: ata_identify_page_supported (STB_LOCAL)
ffffffff8173a0e9-ffffffff8173a129: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817860b0-ffffffff8178615e: ata_identify_page_supported (STB_LOCAL)
ffffffff81789fb9-ffffffff81789ff9: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool ata_identify_page_supported(struct ata_device *dev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2099
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8179ff00-ffffffff8179ffae: ata_identify_page_supported (STB_LOCAL)
ffffffff817a3e09-ffffffff817a3e49: ata_identify_page_supported.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
