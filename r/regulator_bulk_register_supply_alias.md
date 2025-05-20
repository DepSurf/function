# Function: <code>regulator_bulk_register_supply_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc020)
Location: drivers/regulator/core.c:1828
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814dc020-ffffffff814dc104: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152db60)
Location: drivers/regulator/core.c:1880
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8152db60-ffffffff8152dc4b: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559720)
Location: drivers/regulator/core.c:1881
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81559720-ffffffff8155980b: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156ddf0)
Location: drivers/regulator/core.c:1891
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8156ddf0-ffffffff8156df0d: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d2080)
Location: drivers/regulator/core.c:1891
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815d2080-ffffffff815d219d: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160a4a0)
Location: drivers/regulator/core.c:1942
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8160a4a0-ffffffff8160a58b: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81621c30)
Location: drivers/regulator/core.c:2182
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81621c30-ffffffff81621d1b: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2156
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8165cc39-ffffffff8165cca7: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff816554a0-ffffffff8165550e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8167f369-ffffffff8167f3d7: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff816779d0-ffffffff81677a3e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2184
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff817300fe-ffffffff8173016c: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff81728a10-ffffffff81728a7e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2248
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81c0661b-ffffffff81c06689: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff817455c0-ffffffff8174562e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2259
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81bf82b0-ffffffff81bf831d: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff81728f50-ffffffff81729031: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2359
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81cf754c-ffffffff81cf75b9: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff817a8270-ffffffff817a8351: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2406
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81ebf728-ffffffff81ebf797: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff818e2b70-ffffffff818e2c61: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a37c90)
Location: drivers/regulator/core.c:2433
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81a37c90-ffffffff81a37d77: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a81860)
Location: drivers/regulator/core.c:2499
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81a81860-ffffffff81a81947: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad3e40)
Location: drivers/regulator/core.c:2501
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81ad3e40-ffffffff81ad3f27: regulator_bulk_register_supply_alias (STB_GLOBAL)
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
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010840c08)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffff800010840c08-ffff800010840cfc: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094a0c0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
c094a0c0-c094a1a4: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e0e30)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
c0000000008e0e30-c0000000008e0f98: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005228c8)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffe0005228c8-ffffffe000522996: regulator_bulk_register_supply_alias (STB_GLOBAL)
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
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81644dc9-ffffffff81644e37: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff8163d6c0-ffffffff8163d72e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81625249-ffffffff816252b7: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff8161d8b0-ffffffff8161d91e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff816731a9-ffffffff81673217: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff8166b810-ffffffff8166b87e: regulator_bulk_register_supply_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_register_supply_alias(struct device *dev, const const char * *id, struct device *alias_dev, const const char * *alias_id, int num_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2164
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8168d809-ffffffff8168d877: regulator_bulk_register_supply_alias.cold (STB_LOCAL)
ffffffff81685dd0-ffffffff81685e3e: regulator_bulk_register_supply_alias (STB_GLOBAL)
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
