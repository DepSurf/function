# Function: <code>ata_log_supported</code>

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
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81669870)
Location: drivers/ata/libata-core.c:2114
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff81669870-ffffffff816698c7: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d2ec0)
Location: drivers/ata/libata-core.c:2115
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff816d2ec0-ffffffff816d2f17: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170f4f0)
Location: drivers/ata/libata-core.c:2106
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff8170f4f0-ffffffff8170f547: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817319a0)
Location: drivers/ata/libata-core.c:2106
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff817319a0-ffffffff817319f7: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8176d160)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff8176d160-ffffffff8176d1ba: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817911d0)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff817911d0-ffffffff8179122a: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818562b7)
Location: drivers/ata/libata-core.c:2036
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81866537)
Location: drivers/ata/libata-core.c:2036
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81848b76)
Location: drivers/ata/libata-core.c:2036
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d5b26)
Location: drivers/ata/libata-core.c:2042
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a26bf4)
Location: drivers/ata/libata-core.c:2013
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba88b4)
Location: drivers/ata/libata-core.c:2014
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfffd4)
Location: drivers/ata/libata-core.c:2048
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c56044)
Location: drivers/ata/libata-core.c:2183
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
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
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099af78)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffff80001099af78-ffff80001099affc: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6b184)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
c0a6b184-c0a6b1f8: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5e580)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
c000000000a5e580-c000000000a5e62c: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fb670)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffe0005fb670-ffffffe0005fb6f4: ata_log_supported (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81756310)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff81756310-ffffffff8175636a: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817361b0)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff817361b0-ffffffff8173620a: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81786050)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff81786050-ffffffff817860aa: ata_log_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ata_log_supported(struct ata_device *dev, u8 log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179fea0)
Location: drivers/ata/libata-core.c:2090
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_identify_page_supported
```
**Symbols:**

```
ffffffff8179fea0-ffffffff8179fefa: ata_log_supported (STB_LOCAL)
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
