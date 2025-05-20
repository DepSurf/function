# Function: <code>__component_add</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816d4290)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff816d4290-ffffffff816d440c: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816f8150)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff816f8150-ffffffff816f82cc: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817b1130)
Location: drivers/base/component.c:666
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff817b1130-ffffffff817b12a8: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817c5a80)
Location: drivers/base/component.c:666
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff817c5a80-ffffffff817c5bf8: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817a9100)
Location: drivers/base/component.c:663
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff817a9100-ffffffff817a927c: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:658
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81832360-ffffffff818324e7: __component_add (STB_LOCAL)
ffffffff81d02485-ffffffff81d0249a: __component_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:711
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81973910-ffffffff81973aa4: __component_add (STB_LOCAL)
ffffffff81ecaa17-ffffffff81ecaa2c: __component_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:711
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81adee10-ffffffff81adefa4: __component_add (STB_LOCAL)
ffffffff820982af-ffffffff820982c4: __component_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:711
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81b2d0b0-ffffffff81b2d244: __component_add (STB_LOCAL)
ffffffff821192db-ffffffff821192f0: __component_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:711
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81b84850-ffffffff81b84a13: __component_add (STB_LOCAL)
ffffffff821f729e-ffffffff821f72b3: __component_add.cold (STB_LOCAL)
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
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffff8000108e1d40)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffff8000108e1d40-ffff8000108e1ed0: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c09d11d8)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
c09d11d8-c09d135c: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c000000000976f50)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
c000000000976f50-c000000000977180: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffe0005778b6)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffe0005778b6-ffffffe000577a12: __component_add (STB_LOCAL)
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
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816bd940)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff816bd940-ffffffff816bdabc: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81698bf0)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81698bf0-ffffffff81698d6c: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816ebe10)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff816ebe10-ffffffff816ebf8c: __component_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __component_add(struct device *dev, const struct component_ops *ops, int subcomponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81706650)
Location: drivers/base/component.c:664
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_add_typed
```
**Symbols:**

```
ffffffff81706650-ffffffff817067cc: __component_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
