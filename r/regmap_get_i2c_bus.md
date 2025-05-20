# Function: <code>regmap_get_i2c_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8156a710)
Location: drivers/base/regmap/regmap-i2c.c:257
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
```
**Symbols:**

```
ffffffff8156a710-ffffffff8156a807: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff815bf630)
Location: drivers/base/regmap/regmap-i2c.c:257
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff815bf630-ffffffff815bf72c: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff815eea40)
Location: drivers/base/regmap/regmap-i2c.c:257
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff815eea40-ffffffff815eeb3c: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81602c50)
Location: drivers/base/regmap/regmap-i2c.c:257
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81602c50-ffffffff81602d51: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8166b010)
Location: drivers/base/regmap/regmap-i2c.c:257
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff8166b010-ffffffff8166b129: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff816a6a10)
Location: drivers/base/regmap/regmap-i2c.c:253
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff816a6a10-ffffffff816a6b28: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff816c7550)
Location: drivers/base/regmap/regmap-i2c.c:253
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff816c7550-ffffffff816c7668: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817027f0)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff817027f0-ffffffff8170291a: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81726b40)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81726b40-ffffffff81726c6a: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817e31e5)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff817e3070-ffffffff817e31d4: regmap_get_i2c_bus.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817f7e4e)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff817f7cd0-ffffffff817f7e34: regmap_get_i2c_bus.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817dc4a0)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff817dc4a0-ffffffff817dc62c: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81867e00)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81867e00-ffffffff81868027: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff819b0640)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff819b0640-ffffffff819b088a: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b24420)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81b24420-ffffffff81b2466d: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b74540)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81b74540-ffffffff81b7477e: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81bc8390)
Location: drivers/base/regmap/regmap-i2c.c:306
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81bc8390-ffffffff81bc85ce: regmap_get_i2c_bus (STB_LOCAL)
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
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffff80001091bc88)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffff80001091bc88-ffff80001091bdec: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (c0a0152c)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
c0a0152c-c0a01678: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (c0000000009c03b0)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
c0000000009c03b0-c0000000009c0570: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffe00059b77a)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffe00059b77a-ffffffe00059b888: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8171a000)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff8171a000-ffffffff8171a12a: regmap_get_i2c_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct regmap_bus *regmap_get_i2c_bus(struct i2c_client *i2c, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81735360)
Location: drivers/base/regmap/regmap-i2c.c:249
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
```
**Symbols:**

```
ffffffff81735360-ffffffff8173548a: regmap_get_i2c_bus (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
