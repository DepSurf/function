# Function: <code>__power_supply_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff8167f380)
Location: drivers/power/power_supply_core.c:704
Inline: False
Direct callers:
  - drivers/power/power_supply_core.c:power_supply_register
  - drivers/power/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/power_supply_core.c:devm_power_supply_register
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
```
**Symbols:**

```
ffffffff8167f380-ffffffff8167f6b5: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff816e0200)
Location: drivers/power/power_supply_core.c:712
Inline: False
Direct callers:
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/power_supply_core.c:devm_power_supply_register
  - drivers/power/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff816e0200-ffffffff816e052f: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81710670)
Location: drivers/power/supply/power_supply_core.c:712
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81710670-ffffffff8171099f: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81728930)
Location: drivers/power/supply/power_supply_core.c:801
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81728930-ffffffff81728cd9: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8179a0c0)
Location: drivers/power/supply/power_supply_core.c:839
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff8179a0c0-ffffffff8179a45c: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:846
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff817e14f0-ffffffff817e18e2: __power_supply_register (STB_LOCAL)
ffffffff817e1a63-ffffffff817e1a7e: __power_supply_register.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8180cc9d)
Location: drivers/power/supply/power_supply_core.c:984
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff8180cc10-ffffffff8180d00e: __power_supply_register (STB_LOCAL)
ffffffff8180d1e7-ffffffff8180d202: __power_supply_register.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8184e8b0)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff8184e8b0-ffffffff8184ec53: __power_supply_register.part.0 (STB_LOCAL)
ffffffff8184ec60-ffffffff8184ed03: __power_supply_register (STB_LOCAL)
ffffffff8184ef0e-ffffffff8184ef2f: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff818802e0)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff818802e0-ffffffff81880683: __power_supply_register.part.0 (STB_LOCAL)
ffffffff81880690-ffffffff81880733: __power_supply_register (STB_LOCAL)
ffffffff81880918-ffffffff81880939: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1067
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff8194e760-ffffffff8194eb48: __power_supply_register (STB_LOCAL)
ffffffff8194f095-ffffffff8194f0b8: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1091
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81954200-ffffffff819545a2: __power_supply_register (STB_LOCAL)
ffffffff81c25355-ffffffff81c25370: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1091
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81937ff0-ffffffff81938417: __power_supply_register (STB_LOCAL)
ffffffff81c173f9-ffffffff81c1741c: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1114
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff819dc440-ffffffff819dc873: __power_supply_register (STB_LOCAL)
ffffffff81d26340-ffffffff81d2637c: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1283
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81b404c0-ffffffff81b40930: __power_supply_register (STB_LOCAL)
ffffffff81ef2189-ffffffff81ef21bc: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1201
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81cd6ae0-ffffffff81cd6f1c: __power_supply_register (STB_LOCAL)
ffffffff820a7862-ffffffff820a7877: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1340
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81d3ec70-ffffffff81d3f0eb: __power_supply_register (STB_LOCAL)
ffffffff82128c5d-ffffffff82128c72: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1344
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81df55c0-ffffffff81df5a9d: __power_supply_register (STB_LOCAL)
ffffffff8220a5ef-ffffffff8220a604: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffff800010acbde8)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffff800010acbde8-ffff800010acc2a4: __power_supply_register.part.0 (STB_LOCAL)
ffff800010acc2a8-ffff800010acc388: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c0bacd6c)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
c0bacd6c-c0bad268: __power_supply_register.part.0 (STB_LOCAL)
c0bad268-c0bad340: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c000000000bae840)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
c000000000bae840-c000000000baee94: __power_supply_register.part.0 (STB_LOCAL)
c000000000baeea0-c000000000baefc8: __power_supply_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffe0006c9676)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffe0006c9676-ffffffe0006c9aba: __power_supply_register.part.0 (STB_LOCAL)
ffffffe0006c9aba-ffffffe0006c9b66: __power_supply_register (STB_LOCAL)
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
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81828850)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81828850-ffffffff81828bf3: __power_supply_register.part.0 (STB_LOCAL)
ffffffff81828c00-ffffffff81828ca3: __power_supply_register (STB_LOCAL)
ffffffff81828e88-ffffffff81828ea9: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817efee0)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff817efee0-ffffffff817f0283: __power_supply_register.part.0 (STB_LOCAL)
ffffffff817f0290-ffffffff817f0333: __power_supply_register (STB_LOCAL)
ffffffff817f0518-ffffffff817f0539: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81875790)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81875790-ffffffff81875b33: __power_supply_register.part.0 (STB_LOCAL)
ffffffff81875b40-ffffffff81875be3: __power_supply_register (STB_LOCAL)
ffffffff81875dc8-ffffffff81875de9: __power_supply_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct power_supply *__power_supply_register(struct device *parent, const struct power_supply_desc *desc, const struct power_supply_config *cfg, bool ws);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81891130)
Location: drivers/power/supply/power_supply_core.c:994
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:power_supply_register
```
**Symbols:**

```
ffffffff81891130-ffffffff818914d3: __power_supply_register.part.0 (STB_LOCAL)
ffffffff818914e0-ffffffff81891583: __power_supply_register (STB_LOCAL)
ffffffff81891768-ffffffff81891789: __power_supply_register.cold (STB_LOCAL)
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
