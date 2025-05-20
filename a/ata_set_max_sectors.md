# Function: <code>ata_set_max_sectors</code>

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
In drivers/ata/libata-core.c (ffffffff815cc7af)
Location: drivers/ata/libata-core.c:1273
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
In drivers/ata/libata-core.c (ffffffff81624fc7)
Location: drivers/ata/libata-core.c:1276
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
In drivers/ata/libata-core.c (ffffffff81655b67)
Location: drivers/ata/libata-core.c:1283
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
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166dd52)
Location: drivers/ata/libata-core.c:1283
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8166dd52-ffffffff8166de92: ata_set_max_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d7382)
Location: drivers/ata/libata-core.c:1283
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff816d7382-ffffffff816d74c2: ata_set_max_sectors (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8170ff1c)
Location: drivers/ata/libata-core.c:1283
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
In drivers/ata/libata-core.c (ffffffff817323cc)
Location: drivers/ata/libata-core.c:1283
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
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8176d470-ffffffff8176d5d3: ata_set_max_sectors (STB_LOCAL)
ffffffff817711e1-ffffffff81771224: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817914e0-ffffffff81791643: ata_set_max_sectors (STB_LOCAL)
ffffffff817951bc-ffffffff817951ff: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1210
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81855d00-ffffffff81855e5f: ata_set_max_sectors (STB_LOCAL)
ffffffff81859594-ffffffff818595d7: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1210
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81865f70-ffffffff818660d6: ata_set_max_sectors (STB_LOCAL)
ffffffff81c175a7-ffffffff81c175ea: ata_set_max_sectors.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81849831)
Location: drivers/ata/libata-core.c:1210
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
In drivers/ata/libata-core.c (ffffffff818d6891)
Location: drivers/ata/libata-core.c:1214
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1207
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81a26090-ffffffff81a26204: ata_set_max_sectors (STB_LOCAL)
ffffffff81ed6a75-ffffffff81ed6aba: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba8240)
Location: drivers/ata/libata-core.c:1207
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81ba8240-ffffffff81ba840b: ata_set_max_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfeee0)
Location: drivers/ata/libata-core.c:1241
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81bfeee0-ffffffff81bff0ab: ata_set_max_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c54f30)
Location: drivers/ata/libata-core.c:1241
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81c54f30-ffffffff81c550fb: ata_set_max_sectors (STB_LOCAL)
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
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099b348)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffff80001099b348-ffff80001099b4f4: ata_set_max_sectors (STB_LOCAL)
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
In drivers/ata/libata-core.c (c0a6d090)
Location: drivers/ata/libata-core.c:1267
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
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5ea60)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c000000000a5ea60-c000000000a5ec90: ata_set_max_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fb96e)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffe0005fb96e-ffffffe0005fbaa4: ata_set_max_sectors (STB_LOCAL)
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
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81756620-ffffffff81756783: ata_set_max_sectors (STB_LOCAL)
ffffffff8175a2cc-ffffffff8175a30f: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817364c0-ffffffff81736623: ata_set_max_sectors (STB_LOCAL)
ffffffff8173a16c-ffffffff8173a1af: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81786360-ffffffff817864c3: ata_set_max_sectors (STB_LOCAL)
ffffffff8178a03c-ffffffff8178a07f: ata_set_max_sectors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_set_max_sectors(struct ata_device *dev, u64 new_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817a01b0-ffffffff817a0313: ata_set_max_sectors (STB_LOCAL)
ffffffff817a3e8c-ffffffff817a3ecf: ata_set_max_sectors.cold (STB_LOCAL)
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
