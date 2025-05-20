# Function: <code>device_link_remove</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169e0a0)
Location: drivers/base/core.c:385
Inline: False
```
**Symbols:**

```
ffffffff8169e0a0-ffffffff8169e12e: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:486
Inline: False
```
**Symbols:**

```
ffffffff816d8c86-ffffffff816d8c99: device_link_remove.cold (STB_LOCAL)
ffffffff816d65e0-ffffffff816d6653: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa860)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff816fa860-ffffffff816fa8d2: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3050)
Location: drivers/base/core.c:624
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff817b3050-ffffffff817b30c2: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c8010)
Location: drivers/base/core.c:887
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/regulator/core.c:destroy_regulator
```
**Symbols:**

```
ffffffff817c8010-ffffffff817c8078: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab520)
Location: drivers/base/core.c:918
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff817ab520-ffffffff817ab588: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834890)
Location: drivers/base/core.c:930
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81834890-ffffffff818348f8: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819764e0)
Location: drivers/base/core.c:942
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/regulator/core.c:_regulator_put
```
**Symbols:**

```
ffffffff819764e0-ffffffff8197655c: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2600)
Location: drivers/base/core.c:1017
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/regulator/core.c:_regulator_put
```
**Symbols:**

```
ffffffff81ae2600-ffffffff81ae267c: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30520)
Location: drivers/base/core.c:959
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/regulator/core.c:_regulator_put
```
**Symbols:**

```
ffffffff81b30520-ffffffff81b3059c: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87d20)
Location: drivers/base/core.c:962
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/regulator/core.c:_regulator_put
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
```
**Symbols:**

```
ffffffff81b87d20-ffffffff81b87d9c: device_link_remove (STB_GLOBAL)
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
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e45c8)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffff8000108e45c8-ffff8000108e4668: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3010)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
c09d3010-c09d30a8: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c0000000009799e0)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
c0000000009799e0-c000000000979ab0: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005794ee)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffe0005794ee-ffffffe00057956e: device_link_remove (STB_GLOBAL)
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
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0050)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff816c0050-ffffffff816c00c2: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169b300)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff8169b300-ffffffff8169b372: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ee520)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff816ee520-ffffffff816ee592: device_link_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_link_remove(void *consumer, struct device *supplier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709890)
Location: drivers/base/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff81709890-ffffffff81709902: device_link_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
