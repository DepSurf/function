# Function: <code>regulator_register_supply_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dbf60)
Location: drivers/regulator/core.c:1763
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff814dbf60-ffffffff814dc017: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152daa0)
Location: drivers/regulator/core.c:1815
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8152daa0-ffffffff8152db57: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559660)
Location: drivers/regulator/core.c:1816
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81559660-ffffffff81559717: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156dd30)
Location: drivers/regulator/core.c:1826
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8156dd30-ffffffff8156dde7: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1fc0)
Location: drivers/regulator/core.c:1826
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff815d1fc0-ffffffff815d2077: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1877
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8160cc17-ffffffff8160cc7b: regulator_register_supply_alias.cold.63 (STB_LOCAL)
ffffffff8160a440-ffffffff8160a49a: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2117
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81628c1f-ffffffff81628c83: regulator_register_supply_alias.cold.51 (STB_LOCAL)
ffffffff81621bd0-ffffffff81621c2a: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81655467)
Location: drivers/regulator/core.c:2091
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8165cbd6-ffffffff8165cc39: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff81655430-ffffffff81655494: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81677997)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8167f306-ffffffff8167f369: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff81677960-ffffffff816779c4: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817289d7)
Location: drivers/regulator/core.c:2119
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81730099-ffffffff817300fe: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff81728970-ffffffff81728a06: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81745587)
Location: drivers/regulator/core.c:2183
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81c065b6-ffffffff81c0661b: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff81745520-ffffffff817455b6: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728f99)
Location: drivers/regulator/core.c:2194
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff817289d0-ffffffff81728a19: regulator_register_supply_alias.part.0 (STB_LOCAL)
ffffffff81bf824c-ffffffff81bf82b0: regulator_register_supply_alias.part.0.cold (STB_LOCAL)
ffffffff81728e30-ffffffff81728eb3: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a82b9)
Location: drivers/regulator/core.c:2294
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff817a7c20-ffffffff817a7c69: regulator_register_supply_alias.part.0 (STB_LOCAL)
ffffffff81cf74a2-ffffffff81cf7506: regulator_register_supply_alias.part.0.cold (STB_LOCAL)
ffffffff817a8150-ffffffff817a81d3: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e2bb9)
Location: drivers/regulator/core.c:2341
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff818e24a0-ffffffff818e24f8: regulator_register_supply_alias.part.0 (STB_LOCAL)
ffffffff81ebf672-ffffffff81ebf6d6: regulator_register_supply_alias.part.0.cold (STB_LOCAL)
ffffffff818e2a40-ffffffff818e2adb: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a37b80)
Location: drivers/regulator/core.c:2368
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81a37b80-ffffffff81a37c73: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a81750)
Location: drivers/regulator/core.c:2434
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81a81750-ffffffff81a81843: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad3d00)
Location: drivers/regulator/core.c:2436
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81ad3d00-ffffffff81ad3e26: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010840b38)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffff800010840b38-ffff800010840c08: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949ff4)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
c0949ff4-c094a0c0: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e0d10)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
c0000000008e0d10-c0000000008e0e24: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052280e)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffe00052280e-ffffffe0005228c8: regulator_register_supply_alias (STB_GLOBAL)
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
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163d687)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81644d66-ffffffff81644dc9: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff8163d650-ffffffff8163d6b4: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161d877)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff816251e6-ffffffff81625249: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff8161d840-ffffffff8161d8a4: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166b7d7)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff81673146-ffffffff816731a9: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff8166b7a0-ffffffff8166b804: regulator_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_register_supply_alias(struct device *dev, const char *id, struct device *alias_dev, const char *alias_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81685d97)
Location: drivers/regulator/core.c:2099
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
```
**Symbols:**

```
ffffffff8168d7a6-ffffffff8168d809: regulator_register_supply_alias.cold (STB_LOCAL)
ffffffff81685d60-ffffffff81685dc4: regulator_register_supply_alias (STB_GLOBAL)
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
