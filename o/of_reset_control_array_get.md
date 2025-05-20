# Function: <code>of_reset_control_array_get</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d57eb)
Location: drivers/reset/core.c:628
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff815d5570-ffffffff815d5594: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e50b)
Location: drivers/reset/core.c:723
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff8160e340-ffffffff8160e364: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b02b)
Location: drivers/reset/core.c:724
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff8162ae60-ffffffff8162ae84: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ed41)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff8165ea30-ffffffff8165ea54: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168142c)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81681120-ffffffff81681144: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8173256c)
Location: drivers/reset/core.c:869
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff817322f0-ffffffff81732314: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e6bc)
Location: drivers/reset/core.c:943
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff8174e3a0-ffffffff8174e3c4: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817321dc)
Location: drivers/reset/core.c:1161
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81731f20-ffffffff81731f44: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b2853)
Location: drivers/reset/core.c:1161
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff817b2680-ffffffff817b26a4: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818ee204)
Location: drivers/reset/core.c:1174
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff818ee020-ffffffff818ee04c: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a45dc4)
Location: drivers/reset/core.c:1174
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81a45b90-ffffffff81a45bbc: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a8fec4)
Location: drivers/reset/core.c:1174
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81a8fd40-ffffffff81a8fd6c: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae2904)
Location: drivers/reset/core.c:1174
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81ae2780-ffffffff81ae27ac: of_reset_control_array_get (STB_GLOBAL)
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
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084cc60)
Location: drivers/reset/core.c:867
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffff80001084cc60-ffff80001084cdec: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c09590fc)
Location: drivers/reset/core.c:867
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
c09590fc-c0959274: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ebca0)
Location: drivers/reset/core.c:867
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
c0000000008ebca0-c0000000008ebecc: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c4cc)
Location: drivers/reset/core.c:867
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffe00052c4cc-ffffffe00052c60c: of_reset_control_array_get (STB_GLOBAL)
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
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646eac)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81646ba0-ffffffff81646bc4: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162730c)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81627000-ffffffff81627024: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8167526c)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff81674f60-ffffffff81674f84: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *of_reset_control_array_get(struct device_node *np, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f8cc)
Location: drivers/reset/core.c:867
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
```
**Symbols:**

```
ffffffff8168f5c0-ffffffff8168f5e4: of_reset_control_array_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool acquired</code>
</li>
</ul>
</details>
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
