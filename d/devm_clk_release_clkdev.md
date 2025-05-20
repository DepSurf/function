# Function: <code>devm_clk_release_clkdev</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162aba6)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff8162ab93-ffffffff8162abb9: devm_clk_release_clkdev.cold (STB_LOCAL)
ffffffff8162a950-ffffffff8162a9c0: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c410)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff8164c410-ffffffff8164c486: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb070)
Location: drivers/clk/clkdev.c:399
Inline: False
```
**Symbols:**

```
ffffffff816fb070-ffffffff816fb0e6: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff817179c0)
Location: drivers/clk/clkdev.c:399
Inline: False
```
**Symbols:**

```
ffffffff817179c0-ffffffff81717a36: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f8cb0)
Location: drivers/clk/clkdev.c:399
Inline: False
```
**Symbols:**

```
ffffffff816f8cb0-ffffffff816f8d26: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773470)
Location: drivers/clk/clkdev.c:371
Inline: False
```
**Symbols:**

```
ffffffff81773470-ffffffff817734e6: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a8d50)
Location: drivers/clk/clkdev.c:371
Inline: False
```
**Symbols:**

```
ffffffff818a8d50-ffffffff818a8ddf: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bb158)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffff8000107bb158-ffff8000107bb210: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e702c)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
c08e702c-c08e70d8: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe00050a01c)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffe00050a01c-ffffffe00050a0c6: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81612470)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff81612470-ffffffff816124e6: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816069c0)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff816069c0-ffffffff81606a36: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81640250)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff81640250-ffffffff816402c6: devm_clk_release_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_clk_release_clkdev(struct device *dev, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a5a0)
Location: drivers/clk/clkdev.c:399
Inline: True
```
**Symbols:**

```
ffffffff8165a5a0-ffffffff8165a616: devm_clk_release_clkdev (STB_GLOBAL)
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
