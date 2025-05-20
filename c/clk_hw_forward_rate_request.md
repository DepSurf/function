# Function: <code>clk_hw_forward_rate_request</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_hw_forward_rate_request(const struct clk_hw *hw, const struct clk_rate_request *old_req, const struct clk_hw *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fdef0)
Location: drivers/clk/clk.c:1526
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff819fdef0-ffffffff819fdf3b: clk_hw_forward_rate_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_hw_forward_rate_request(const struct clk_hw *hw, const struct clk_rate_request *old_req, const struct clk_hw *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a40cf0)
Location: drivers/clk/clk.c:1570
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff81a40cf0-ffffffff81a40d3b: clk_hw_forward_rate_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_hw_forward_rate_request(const struct clk_hw *hw, const struct clk_rate_request *old_req, const struct clk_hw *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8c700)
Location: drivers/clk/clk.c:1570
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
  - drivers/clk/clk-composite.c:clk_composite_determine_rate
```
**Symbols:**

```
ffffffff81a8c700-ffffffff81a8c74b: clk_hw_forward_rate_request (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
