# Function: <code>__pm_clk_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff8155d130)
Location: drivers/base/power/clock_ops.c:74
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_add_clk
```
**Symbols:**

```
ffffffff8155d130-ffffffff8155d2ac: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815b1560)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff815b1560-ffffffff815b16e0: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815e0840)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff815e0840-ffffffff815e09c0: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815f56a0)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff815f56a0-ffffffff815f5835: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff8165d5c0)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff8165d5c0-ffffffff8165d755: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81699330)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff81699330-ffffffff816994a7: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff816b9b90)
Location: drivers/base/power/clock_ops.c:75
Inline: False
```
**Symbols:**

```
ffffffff816b9b90-ffffffff816b9d07: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff816f3dd0-ffffffff816f3f5c: __pm_clk_add (STB_LOCAL)
ffffffff816f438c-ffffffff816f43a9: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff817181d0-ffffffff8171835c: __pm_clk_add (STB_LOCAL)
ffffffff8171878c-ffffffff817187a9: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff817d3ec0-ffffffff817d404c: __pm_clk_add (STB_LOCAL)
ffffffff817d435c-ffffffff817d4379: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff817e8910-ffffffff817e8a9c: __pm_clk_add (STB_LOCAL)
ffffffff81c0f12e-ffffffff81c0f14b: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff817cd0b0-ffffffff817cd27b: __pm_clk_add (STB_LOCAL)
ffffffff81c0126e-ffffffff81c0128b: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff81857840-ffffffff81857a17: __pm_clk_add (STB_LOCAL)
ffffffff81d041af-ffffffff81d041e0: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff8199dbf0-ffffffff8199ddd9: __pm_clk_add (STB_LOCAL)
ffffffff81eccab8-ffffffff81eccae7: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff81b0f3b0-ffffffff81b0f5b0: __pm_clk_add (STB_LOCAL)
ffffffff82098b00-ffffffff82098b14: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff81b5d480-ffffffff81b5d680: __pm_clk_add (STB_LOCAL)
ffffffff82119ab7-ffffffff82119acb: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:195
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
```
**Symbols:**

```
ffffffff81bb0d30-ffffffff81bb0f5f: __pm_clk_add (STB_LOCAL)
ffffffff821f798f-ffffffff821f79a3: __pm_clk_add.cold (STB_LOCAL)
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
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffff80001090b200)
Location: drivers/base/power/clock_ops.c:80
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
```
**Symbols:**

```
ffff80001090b200-ffff80001090b3e4: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (c09f4590)
Location: drivers/base/power/clock_ops.c:80
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
```
**Symbols:**

```
c09f4590-c09f472c: __pm_clk_add (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffe000590d6c)
Location: drivers/base/power/clock_ops.c:80
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
```
**Symbols:**

```
ffffffe000590d6c-ffffffe000590efa: __pm_clk_add (STB_LOCAL)
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
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff816de500-ffffffff816de68c: __pm_clk_add (STB_LOCAL)
ffffffff816deabc-ffffffff816dead9: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff816b8b60-ffffffff816b8ce6: __pm_clk_add (STB_LOCAL)
ffffffff816b90f6-ffffffff816b9113: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff8170be90-ffffffff8170c01c: __pm_clk_add (STB_LOCAL)
ffffffff8170c44c-ffffffff8170c469: __pm_clk_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pm_clk_add(struct device *dev, const char *con_id, struct clk *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:80
Inline: False
```
**Symbols:**

```
ffffffff817265b0-ffffffff81726733: __pm_clk_add (STB_LOCAL)
ffffffff81726d96-ffffffff81726db3: __pm_clk_add.cold (STB_LOCAL)
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
