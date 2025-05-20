# Function: <code>devm_clk_notifier_register</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171a170)
Location: drivers/clk/clk.c:4423
Inline: False
```
**Symbols:**

```
ffffffff8171a170-ffffffff8171a1ee: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fb470)
Location: drivers/clk/clk.c:4427
Inline: False
```
**Symbols:**

```
ffffffff816fb470-ffffffff816fb4ee: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81775bf0)
Location: drivers/clk/clk.c:4454
Inline: False
```
**Symbols:**

```
ffffffff81775bf0-ffffffff81775c75: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818ac3a0)
Location: drivers/clk/clk.c:4527
Inline: False
```
**Symbols:**

```
ffffffff818ac3a0-ffffffff818ac441: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f7b10)
Location: drivers/clk/clk.c:4669
Inline: False
```
**Symbols:**

```
ffffffff819f7b10-ffffffff819f7bb1: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a403c0)
Location: drivers/clk/clk.c:4728
Inline: False
```
**Symbols:**

```
ffffffff81a403c0-ffffffff81a40473: devm_clk_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_clk_notifier_register(struct device *dev, struct clk *clk, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8bde0)
Location: drivers/clk/clk.c:4774
Inline: False
```
**Symbols:**

```
ffffffff81a8bde0-ffffffff81a8be93: devm_clk_notifier_register (STB_GLOBAL)
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
