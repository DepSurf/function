# Function: <code>devm_regulator_unregister_supply_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff814dea30)
Location: drivers/regulator/devres.c:328
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff814dea30-ffffffff814dea96: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8152ff90)
Location: drivers/regulator/devres.c:331
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8152ff90-ffffffff8152fff6: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8155c5e0)
Location: drivers/regulator/devres.c:328
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8155c5e0-ffffffff8155c646: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81571000)
Location: drivers/regulator/devres.c:314
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81571000-ffffffff81571057: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815d52a0)
Location: drivers/regulator/devres.c:314
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff815d52a0-ffffffff815d52f7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8160e0a0)
Location: drivers/regulator/devres.c:314
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8160e0a0-ffffffff8160e0f7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8162abc0)
Location: drivers/regulator/devres.c:314
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8162abc0-ffffffff8162ac17: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8165e93e)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8165e93e-ffffffff8165e951: devm_regulator_unregister_supply_alias.cold (STB_LOCAL)
ffffffff8165e780-ffffffff8165e7d9: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81680ef0)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81680ef0-ffffffff81680f47: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817321d6)
Location: drivers/regulator/devres.c:309
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81732070-ffffffff817320c7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8174e2f6)
Location: drivers/regulator/devres.c:311
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8174e190-ffffffff8174e1e7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731e76)
Location: drivers/regulator/devres.c:311
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81731d10-ffffffff81731d67: devm_regulator_unregister_supply_alias (STB_GLOBAL)
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
In drivers/regulator/devres.c (ffffffff81cf8419)
Location: drivers/regulator/devres.c:270
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
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
In drivers/regulator/devres.c (ffffffff81ec051c)
Location: drivers/regulator/devres.c:270
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
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
In drivers/regulator/devres.c (ffffffff81a44cd7)
Location: drivers/regulator/devres.c:492
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
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
In drivers/regulator/devres.c (ffffffff81a8ee87)
Location: drivers/regulator/devres.c:492
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
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
In drivers/regulator/devres.c (ffffffff81ae16f7)
Location: drivers/regulator/devres.c:492
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
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
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffff80001084ac80)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffff80001084ac80-ffff80001084ad00: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c09541c0)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
c09541c0-c0954258: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0000000008e8720)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
c0000000008e8720-c0000000008e87a8: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffe00052a8ac)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffe00052a8ac-ffffffe00052a8fc: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81646970)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81646970-ffffffff816469c7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81626dd0)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81626dd0-ffffffff81626e27: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81674d30)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff81674d30-ffffffff81674d87: devm_regulator_unregister_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_supply_alias(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8168f390)
Location: drivers/regulator/devres.c:309
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
```
**Symbols:**

```
ffffffff8168f390-ffffffff8168f3e7: devm_regulator_unregister_supply_alias (STB_GLOBAL)
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
