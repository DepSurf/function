# Function: <code>extcon_get_property</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177fa90)
Location: drivers/extcon/extcon.c:619
Inline: False
```
**Symbols:**

```
ffffffff8177fa90-ffffffff8177fc59: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179e790)
Location: drivers/extcon/extcon.c:633
Inline: False
```
**Symbols:**

```
ffffffff8179e790-ffffffff8179e999: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818158f0)
Location: drivers/extcon/extcon.c:622
Inline: False
```
**Symbols:**

```
ffffffff818158f0-ffffffff81815af9: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185f7d0)
Location: drivers/extcon/extcon.c:623
Inline: False
```
**Symbols:**

```
ffffffff8185f7d0-ffffffff8185f9a6: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187f170)
Location: drivers/extcon/extcon.c:623
Inline: False
```
**Symbols:**

```
ffffffff8187f170-ffffffff8187f346: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9770)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffffffff818c9770-ffffffff818c9956: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fbbc0)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffffffff818fbbc0-ffffffff818fbda6: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2c90)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
ffffffff819d2c90-ffffffff819d2e6a: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2870)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
ffffffff819d2870-ffffffff819d2a4a: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7730)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
ffffffff819b7730-ffffffff819b790c: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
ffffffff81d33626-ffffffff81d3364f: extcon_get_property.cold (STB_LOCAL)
ffffffff81a66460-ffffffff81a666ce: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:604
Inline: True
```
**Symbols:**

```
ffffffff81effa9b-ffffffff81effac2: extcon_get_property.cold (STB_LOCAL)
ffffffff81bd7970-ffffffff81bd7bc7: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:614
Inline: True
```
**Symbols:**

```
ffffffff820aa5e1-ffffffff820aa608: extcon_get_property.cold (STB_LOCAL)
ffffffff81d848a0-ffffffff81d84af7: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:624
Inline: True
```
**Symbols:**

```
ffffffff8212bada-ffffffff8212baf3: extcon_get_property.cold (STB_LOCAL)
ffffffff81df2c40-ffffffff81df2e8d: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:624
Inline: True
```
**Symbols:**

```
ffffffff8220d76f-ffffffff8220d788: extcon_get_property.cold (STB_LOCAL)
ffffffff81ea9290-ffffffff81ea94dd: extcon_get_property (STB_GLOBAL)
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
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b89a08)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffff800010b89a08-ffff800010b89c5c: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d92c)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
c0c6d92c-c0c6dae0: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c67700)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
c000000000c67700-c000000000c679b8: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe000730f56)
Location: drivers/extcon/extcon.c:615
Inline: True
```
**Symbols:**

```
ffffffe000730f56-ffffffe0007310e8: extcon_get_property (STB_GLOBAL)
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
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189cef0)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffffffff8189cef0-ffffffff8189d0d6: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec5e0)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffffffff818ec5e0-ffffffff818ec7c6: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_get_property(struct extcon_dev *edev, unsigned int id, unsigned int prop, union extcon_property_value *prop_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190d660)
Location: drivers/extcon/extcon.c:615
Inline: False
```
**Symbols:**

```
ffffffff8190d660-ffffffff8190d846: extcon_get_property (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
