# Function: <code>clk_core_reparent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clk_core_reparent(struct clk_core *core, struct clk_core *new_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e4cb0)
Location: drivers/clk/clk.c:1714
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_hw_reparent
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff816e4cb0-ffffffff816e4cda: clk_core_reparent (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8174cdbb)
Location: drivers/clk/clk.c:1738
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8153513a)
Location: drivers/clk/clk.c:1738
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8154852f)
Location: drivers/clk/clk.c:1740
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff815ab9af)
Location: drivers/clk/clk.c:1851
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff815e399f)
Location: drivers/clk/clk.c:2149
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff815fdd7a)
Location: drivers/clk/clk.c:2262
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81630c7b)
Location: drivers/clk/clk.c:2398
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81652a3b)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8170253b)
Location: drivers/clk/clk.c:2427
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8171f96b)
Location: drivers/clk/clk.c:2442
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8170098b)
Location: drivers/clk/clk.c:2455
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8177b19b)
Location: drivers/clk/clk.c:2455
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff818b198a)
Location: drivers/clk/clk.c:2472
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff819fdf6a)
Location: drivers/clk/clk.c:2676
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81a46bea)
Location: drivers/clk/clk.c:2721
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81a926da)
Location: drivers/clk/clk.c:2721
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffff8000107c336c)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eeda8)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffe000510d6a)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81618a9b)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8160cfcb)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff8164687b)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
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
In drivers/clk/clk.c (ffffffff81660e0b)
Location: drivers/clk/clk.c:2406
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_reparent
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
