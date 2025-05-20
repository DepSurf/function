# Function: <code>devm_clkdev_release</code>

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
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a8a0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff8162a8a0-ffffffff8162a8b3: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c360)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff8164c360-ffffffff8164c373: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb470)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff816fb470-ffffffff816fb4cb: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717dc0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff81717dc0-ffffffff81717e1b: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f90b0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff816f90b0-ffffffff816f910b: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773810)
Location: drivers/clk/clkdev.c:349
Inline: False
```
**Symbols:**

```
ffffffff81773810-ffffffff8177386b: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a9160)
Location: drivers/clk/clkdev.c:349
Inline: False
```
**Symbols:**

```
ffffffff818a9160-ffffffff818a91c2: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_clkdev_release(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3b37)
Location: drivers/clk/clkdev.c:349
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
**Symbols:**

```
ffffffff819f3a60-ffffffff819f3ac0: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_clkdev_release(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c270)
Location: drivers/clk/clkdev.c:349
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
**Symbols:**

```
ffffffff81a3c110-ffffffff81a3c170: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_clkdev_release(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87b30)
Location: drivers/clk/clkdev.c:349
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
**Symbols:**

```
ffffffff81a879d0-ffffffff81a87a30: devm_clkdev_release (STB_LOCAL)
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
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bb070)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffff8000107bb070-ffff8000107bb09c: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e6f80)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
c08e6f80-c08e6fa0: devm_clkdev_release (STB_LOCAL)
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
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe000509f6c)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffe000509f6c-ffffffe000509f96: devm_clkdev_release (STB_LOCAL)
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
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816123c0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff816123c0-ffffffff816123d3: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606910)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff81606910-ffffffff81606923: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816401a0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff816401a0-ffffffff816401b3: devm_clkdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devm_clkdev_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a4f0)
Location: drivers/clk/clkdev.c:377
Inline: False
```
**Symbols:**

```
ffffffff8165a4f0-ffffffff8165a503: devm_clkdev_release (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, res</code> ➡️ <code>res</code>
</li>
</ul>
</details>
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
