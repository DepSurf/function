# Function: <code>clk_composite_determine_rate_for_parent</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int clk_composite_determine_rate_for_parent(struct clk_hw *rate_hw, struct clk_rate_request *req, struct clk_hw *parent_hw, const struct clk_ops *rate_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff818b4f20)
Location: drivers/clk/clk-composite.c:45
Inline: True
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff818b4f20-ffffffff818b4fa0: clk_composite_determine_rate_for_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_composite_determine_rate_for_parent(struct clk_hw *rate_hw, struct clk_rate_request *req, struct clk_hw *parent_hw, const struct clk_ops *rate_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a01c00)
Location: drivers/clk/clk-composite.c:45
Inline: True
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff81a01c00-ffffffff81a01c82: clk_composite_determine_rate_for_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_composite_determine_rate_for_parent(struct clk_hw *rate_hw, struct clk_rate_request *req, struct clk_hw *parent_hw, const struct clk_ops *rate_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a4a910)
Location: drivers/clk/clk-composite.c:45
Inline: True
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff81a4a910-ffffffff81a4a992: clk_composite_determine_rate_for_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_composite_determine_rate_for_parent(struct clk_hw *rate_hw, struct clk_rate_request *req, struct clk_hw *parent_hw, const struct clk_ops *rate_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a96490)
Location: drivers/clk/clk-composite.c:45
Inline: True
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff81a96490-ffffffff81a96512: clk_composite_determine_rate_for_parent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
