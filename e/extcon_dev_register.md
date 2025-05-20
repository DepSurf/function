# Function: <code>extcon_dev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816ef030)
Location: drivers/extcon/extcon.c:765
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff816ef030-ffffffff816ef77f: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81753d60)
Location: drivers/extcon/extcon.c:576
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81753d60-ffffffff817544b0: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81780300)
Location: drivers/extcon/extcon.c:1052
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81780300-ffffffff81780a64: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179ee60)
Location: drivers/extcon/extcon.c:1094
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff8179ee60-ffffffff8179f753: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815fc0)
Location: drivers/extcon/extcon.c:1089
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81815fc0-ffffffff818168a7: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1090
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81860897-ffffffff818608af: extcon_dev_register.cold.17 (STB_LOCAL)
ffffffff8185fe90-ffffffff81860821: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187f830)
Location: drivers/extcon/extcon.c:1090
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff8187f830-ffffffff8187ffe1: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff818ca5ba-ffffffff818ca5ee: extcon_dev_register.cold (STB_LOCAL)
ffffffff818c9e30-ffffffff818ca528: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff818fca0a-ffffffff818fca3e: extcon_dev_register.cold (STB_LOCAL)
ffffffff818fc280-ffffffff818fc978: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff819d36a9-ffffffff819d36dd: extcon_dev_register.cold (STB_LOCAL)
ffffffff819d2e70-ffffffff819d3625: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81c2f627-ffffffff81c2f642: extcon_dev_register.cold (STB_LOCAL)
ffffffff819d2a50-ffffffff819d3200: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81c218ec-ffffffff81c21907: extcon_dev_register.cold (STB_LOCAL)
ffffffff819b7d00-ffffffff819b84a9: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81d3364f-ffffffff81d3366a: extcon_dev_register.cold (STB_LOCAL)
ffffffff81a66c00-ffffffff81a673a9: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1076
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81effac2-ffffffff81effaf1: extcon_dev_register.cold (STB_LOCAL)
ffffffff81bd8110-ffffffff81bd88fd: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d84b10)
Location: drivers/extcon/extcon.c:1086
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81d84b10-ffffffff81d8531f: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df30c0)
Location: drivers/extcon/extcon.c:1247
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81df30c0-ffffffff81df3782: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea9710)
Location: drivers/extcon/extcon.c:1247
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff81ea9710-ffffffff81ea9de4: extcon_dev_register (STB_GLOBAL)
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
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b88c28)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffff800010b88c28-ffff800010b89340: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6daf8)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
c0c6daf8-c0c6e1a4: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c68d60)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
c000000000c68d60-c000000000c695fc: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe000731c9c)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffe000731c9c-ffffffe00073226e: extcon_dev_register (STB_GLOBAL)
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
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff8189dd3a-ffffffff8189dd6e: extcon_dev_register.cold (STB_LOCAL)
ffffffff8189d5b0-ffffffff8189dca8: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff818ed42a-ffffffff818ed45e: extcon_dev_register.cold (STB_LOCAL)
ffffffff818ecca0-ffffffff818ed398: extcon_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int extcon_dev_register(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:1082
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff8190e4aa-ffffffff8190e4de: extcon_dev_register.cold (STB_LOCAL)
ffffffff8190dd20-ffffffff8190e418: extcon_dev_register (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
