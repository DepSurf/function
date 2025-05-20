# Function: <code>ata_read_native_max_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cc582)
Location: drivers/ata/libata-core.c:1222
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81624d85)
Location: drivers/ata/libata-core.c:1225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81655925)
Location: drivers/ata/libata-core.c:1232
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816699c0)
Location: drivers/ata/libata-core.c:1232
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff816699c0-ffffffff81669bac: ata_read_native_max_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d3010)
Location: drivers/ata/libata-core.c:1232
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff816d3010-ffffffff816d31fc: ata_read_native_max_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170fd5c)
Location: drivers/ata/libata-core.c:1232
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8173220c)
Location: drivers/ata/libata-core.c:1232
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8176d270-ffffffff8176d468: ata_read_native_max_address (STB_LOCAL)
ffffffff8177119e-ffffffff817711e1: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817912e0-ffffffff817914d8: ata_read_native_max_address (STB_LOCAL)
ffffffff81795179-ffffffff817951bc: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1159
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81855b10-ffffffff81855d00: ata_read_native_max_address (STB_LOCAL)
ffffffff81859551-ffffffff81859594: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1159
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81865d80-ffffffff81865f70: ata_read_native_max_address (STB_LOCAL)
ffffffff81c17564-ffffffff81c175a7: ata_read_native_max_address.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8184963b)
Location: drivers/ata/libata-core.c:1159
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
In drivers/ata/libata-core.c (ffffffff818d669b)
Location: drivers/ata/libata-core.c:1163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
In drivers/ata/libata-core.c (ffffffff81a2754a)
Location: drivers/ata/libata-core.c:1156
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
In drivers/ata/libata-core.c (ffffffff81ba99da)
Location: drivers/ata/libata-core.c:1156
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
In drivers/ata/libata-core.c (ffffffff81c00a3a)
Location: drivers/ata/libata-core.c:1190
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
In drivers/ata/libata-core.c (ffffffff81c56aaa)
Location: drivers/ata/libata-core.c:1190
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
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
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099b118)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffff80001099b118-ffff80001099b344: ata_read_native_max_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6c580)
Location: drivers/ata/libata-core.c:1216
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5e790)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c000000000a5e790-c000000000a5ea60: ata_read_native_max_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fb7d8)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffe0005fb7d8-ffffffe0005fb96e: ata_read_native_max_address (STB_LOCAL)
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
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81756420-ffffffff81756618: ata_read_native_max_address (STB_LOCAL)
ffffffff8175a289-ffffffff8175a2cc: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817362c0-ffffffff817364b8: ata_read_native_max_address (STB_LOCAL)
ffffffff8173a129-ffffffff8173a16c: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81786160-ffffffff81786358: ata_read_native_max_address (STB_LOCAL)
ffffffff81789ff9-ffffffff8178a03c: ata_read_native_max_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_read_native_max_address(struct ata_device *dev, u64 *max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8179ffb0-ffffffff817a01a8: ata_read_native_max_address (STB_LOCAL)
ffffffff817a3e49-ffffffff817a3e8c: ata_read_native_max_address.cold (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
