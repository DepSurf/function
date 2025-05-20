# Function: <code>of_set_phy_supported</code>

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
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1304
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1544
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1669
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1677
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1725
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1760
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2090
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81797260)
Location: drivers/net/phy/phy-core.c:239
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81797260-ffffffff8179726b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817bad50)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff817bad50-ffffffff817bad5b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882600)
Location: drivers/net/phy/phy-core.c:252
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81882600-ffffffff8188260b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890d30)
Location: drivers/net/phy/phy-core.c:289
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81890d30-ffffffff81890d3b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81873610)
Location: drivers/net/phy/phy-core.c:289
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81873610-ffffffff8187361b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903eb0)
Location: drivers/net/phy/phy-core.c:290
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81903eb0-ffffffff81903ebb: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a56930)
Location: drivers/net/phy/phy-core.c:283
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81a56930-ffffffff81a5693f: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be0670)
Location: drivers/net/phy/phy-core.c:366
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81be0670-ffffffff81be067f: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37f80)
Location: drivers/net/phy/phy-core.c:369
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81c37f80-ffffffff81c37f8f: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81ced310)
Location: drivers/net/phy/phy-core.c:371
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff81ced310-ffffffff81ced31f: of_set_phy_supported (STB_GLOBAL)
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
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d36c0)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffff8000109d36c0-ffff8000109d3784: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb52c)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
c0abb52c-c0abb600: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93b20)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
c000000000a93b20-c000000000a93c18: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fde4)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffe00061fde4-ffffffe00061fe72: of_set_phy_supported (STB_GLOBAL)
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
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f820)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff8177f820-ffffffff8177f82b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f5c0)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff8175f5c0-ffffffff8175f5cb: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817afbd0)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff817afbd0-ffffffff817afbdb: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void of_set_phy_supported(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9b60)
Location: drivers/net/phy/phy-core.c:244
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
**Symbols:**

```
ffffffff817c9b60-ffffffff817c9b6b: of_set_phy_supported (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
