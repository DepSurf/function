# Function: <code>phy_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141c910)
Location: drivers/phy/phy-core.c:684
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8141c910-ffffffff8141caf5: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81465010)
Location: drivers/phy/phy-core.c:699
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81465010-ffffffff814651f5: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81484310)
Location: drivers/phy/phy-core.c:714
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81484310-ffffffff814844f5: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148da10)
Location: drivers/phy/phy-core.c:714
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8148da10-ffffffff8148dbc2: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c9b70)
Location: drivers/phy/phy-core.c:733
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff814c9b70-ffffffff814c9d22: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814faba0)
Location: drivers/phy/phy-core.c:753
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff814faba0-ffffffff814fad45: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150f6a0)
Location: drivers/phy/phy-core.c:817
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8150f6a0-ffffffff8150f856: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:824
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8153dfe9-ffffffff8153e026: phy_create.cold (STB_LOCAL)
ffffffff8153dcf0-ffffffff8153de77: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8155ee09-ffffffff8155ee2c: phy_create.cold (STB_LOCAL)
ffffffff8155eb00-ffffffff8155ec92: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:867
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81601117-ffffffff8160113a: phy_create.cold (STB_LOCAL)
ffffffff816008a0-ffffffff81600a32: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:867
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81bf4db2-ffffffff81bf4dd5: phy_create.cold (STB_LOCAL)
ffffffff81625790-ffffffff81625922: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:897
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81be6ced-ffffffff81be6d10: phy_create.cold (STB_LOCAL)
ffffffff81609250-ffffffff816093e2: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:899
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81ce0179-ffffffff81ce019c: phy_create.cold (STB_LOCAL)
ffffffff81677ec0-ffffffff81678052: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:937
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81ea68cf-ffffffff81ea68ee: phy_create.cold (STB_LOCAL)
ffffffff81793140-ffffffff817932e8: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a7d10)
Location: drivers/phy/phy-core.c:937
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff818a7d10-ffffffff818a7ed7: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eab20)
Location: drivers/phy/phy-core.c:948
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff818eab20-ffffffff818ead12: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81932000)
Location: drivers/phy/phy-core.c:948
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81932000-ffffffff81932221: phy_create (STB_GLOBAL)
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
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010686a10)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffff800010686a10-ffff800010686bd4: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082a77c)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
c082a77c-c082a918: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c000000000822ea0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
c000000000822ea0-c000000000823138: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe00049712e)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffe00049712e-ffffffe0004972d4: phy_create (STB_GLOBAL)
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
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff815573f9-ffffffff8155741c: phy_create.cold (STB_LOCAL)
ffffffff815570f0-ffffffff81557282: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff815478b9-ffffffff815478dc: phy_create.cold (STB_LOCAL)
ffffffff815475b0-ffffffff81547742: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff81553139-ffffffff8155315c: phy_create.cold (STB_LOCAL)
ffffffff81552e30-ffffffff81552fc2: phy_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct phy *phy_create(struct device *dev, struct device_node *node, const struct phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_create
```
**Symbols:**

```
ffffffff8156cfc9-ffffffff8156cfec: phy_create.cold (STB_LOCAL)
ffffffff8156ccc0-ffffffff8156ce52: phy_create (STB_GLOBAL)
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
