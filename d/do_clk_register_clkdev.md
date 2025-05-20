# Function: <code>do_clk_register_clkdev</code>

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
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a720)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff8162a720-ffffffff8162a772: do_clk_register_clkdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c1e0)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff8164c1e0-ffffffff8164c232: do_clk_register_clkdev (STB_LOCAL)
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
In drivers/clk/clkdev.c (ffffffff816fb385)
Location: drivers/clk/clkdev.c:310
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff81717cd5)
Location: drivers/clk/clkdev.c:310
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff816f8fc5)
Location: drivers/clk/clkdev.c:310
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff8177371c)
Location: drivers/clk/clkdev.c:282
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff818a904c)
Location: drivers/clk/clkdev.c:282
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff819f3ae1)
Location: drivers/clk/clkdev.c:282
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff81a3c213)
Location: drivers/clk/clkdev.c:282
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
In drivers/clk/clkdev.c (ffffffff81a87ad3)
Location: drivers/clk/clkdev.c:282
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
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
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bae90)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffff8000107bae90-ffff8000107baf18: do_clk_register_clkdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e6df8)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
c08e6df8-c08e6e54: do_clk_register_clkdev (STB_LOCAL)
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
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe000509e06)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffe000509e06-ffffffe000509e80: do_clk_register_clkdev (STB_LOCAL)
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
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81612240)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff81612240-ffffffff81612292: do_clk_register_clkdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606790)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff81606790-ffffffff816067e2: do_clk_register_clkdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81640020)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff81640020-ffffffff81640072: do_clk_register_clkdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_clk_register_clkdev(struct clk_hw *hw, struct clk_lookup **cl, const char *con_id, const char *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a370)
Location: drivers/clk/clkdev.c:310
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_hw_register_clkdev
  - drivers/clk/clkdev.c:clk_register_clkdev
```
**Symbols:**

```
ffffffff8165a370-ffffffff8165a3c2: do_clk_register_clkdev (STB_LOCAL)
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
