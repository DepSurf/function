# Function: <code>_is_valid_div</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool _is_valid_div(const struct clk_div_table *table, unsigned int div, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff816e8ee0)
Location: drivers/clk/clk-divider.c:163
Inline: True
Direct callers:
  - drivers/clk/clk-divider.c:divider_get_val
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
**Symbols:**

```
ffffffff816e8ee0-ffffffff816e8f2b: _is_valid_div (STB_LOCAL)
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
In drivers/clk/clk-divider.c (ffffffff8174d3c5)
Location: drivers/clk/clk-divider.c:162
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff81535c35)
Location: drivers/clk/clk-divider.c:162
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff81548f95)
Location: drivers/clk/clk-divider.c:162
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff815ac514)
Location: drivers/clk/clk-divider.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff815e4634)
Location: drivers/clk/clk-divider.c:159
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff815fea24)
Location: drivers/clk/clk-divider.c:156
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff816310c5)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff81652df5)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81702a39)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8171fb09)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81700d55)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8177b57a)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff818b1de8)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff819fe428)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a470e8)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a92b88)
Location: drivers/clk/clk-divider.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffff8000107c37f4)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (c08ef7e0)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/clk/ti/divider.c (c0916b8c)
Location: drivers/clk/ti/divider.c:134
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:ti_clk_divider_round_rate
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffe0005110c0)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff81618e55)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff8160d385)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff81646c35)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
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
In drivers/clk/clk-divider.c (ffffffff816611c5)
Location: drivers/clk/clk-divider.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
