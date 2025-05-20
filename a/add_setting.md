# Function: <code>add_setting</code>

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
In drivers/pinctrl/core.c (ffffffff8141e4a8)
Location: drivers/pinctrl/core.c:710
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
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
In drivers/pinctrl/core.c (ffffffff81466bcc)
Location: drivers/pinctrl/core.c:723
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
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
In drivers/pinctrl/core.c (ffffffff81485ebc)
Location: drivers/pinctrl/core.c:723
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
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
In drivers/pinctrl/core.c (ffffffff8148f922)
Location: drivers/pinctrl/core.c:909
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
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
In drivers/pinctrl/core.c (ffffffff814cbad2)
Location: drivers/pinctrl/core.c:909
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
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
In drivers/pinctrl/core.c (ffffffff814fca70)
Location: drivers/pinctrl/core.c:909
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
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
In drivers/pinctrl/core.c (ffffffff815114d0)
Location: drivers/pinctrl/core.c:937
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153fae2)
Location: drivers/pinctrl/core.c:913
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81560982)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:942
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff816031d0-ffffffff816033a3: add_setting (STB_LOCAL)
ffffffff81603ef0-ffffffff81603f0d: add_setting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:943
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff816280e0-ffffffff816282b3: add_setting (STB_LOCAL)
ffffffff81bf5115-ffffffff81bf5132: add_setting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:943
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8160bbc0-ffffffff8160bd93: add_setting (STB_LOCAL)
ffffffff81be6f8c-ffffffff81be6fa9: add_setting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:943
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8167a8d0-ffffffff8167aaa3: add_setting (STB_LOCAL)
ffffffff81ce049e-ffffffff81ce04bb: add_setting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:943
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff81795f60-ffffffff8179616b: add_setting (STB_LOCAL)
ffffffff81ea6bed-ffffffff81ea6c0a: add_setting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ab650)
Location: drivers/pinctrl/core.c:944
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff818ab650-ffffffff818ab869: add_setting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ee590)
Location: drivers/pinctrl/core.c:948
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff818ee590-ffffffff818ee7a9: add_setting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_setting(struct pinctrl *p, struct pinctrl_dev *pctldev, const struct pinctrl_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81935d50)
Location: drivers/pinctrl/core.c:962
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff81935d50-ffffffff81935f40: add_setting (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d4a0)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d7bc)
Location: drivers/pinctrl/pinctrl-single.c:843
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082f508)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pinctrl/pinctrl-single.c (c083fd4c)
Location: drivers/pinctrl/pinctrl-single.c:843
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000827080)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000834b88)
Location: drivers/pinctrl/pinctrl-single.c:843
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499672)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1be2)
Location: drivers/pinctrl/pinctrl-single.c:843
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81558f72)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81549432)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81554cb2)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156eb42)
Location: drivers/pinctrl/core.c:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
