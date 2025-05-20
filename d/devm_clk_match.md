# Function: <code>devm_clk_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816e3c50)
Location: drivers/clk/clk-devres.c:37
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816e4b30)
Location: drivers/clk/clk.c:2734
Inline: False
```
**Symbols:**

```
ffffffff816e3c50-ffffffff816e3c85: devm_clk_match (STB_LOCAL)
ffffffff816e4b30-ffffffff816e4b5d: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81747f90)
Location: drivers/clk/clk-devres.c:37
Inline: True
```
```
In drivers/clk/clk.c (ffffffff817492c0)
Location: drivers/clk/clk.c:2813
Inline: False
```
**Symbols:**

```
ffffffff81747f90-ffffffff81747fc5: devm_clk_match (STB_LOCAL)
ffffffff817492c0-ffffffff817492ed: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81530800)
Location: drivers/clk/clk-devres.c:37
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81531b40)
Location: drivers/clk/clk.c:2816
Inline: False
```
**Symbols:**

```
ffffffff81530800-ffffffff81530835: devm_clk_match (STB_LOCAL)
ffffffff81531b40-ffffffff81531b6d: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81543980)
Location: drivers/clk/clk-devres.c:73
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81544ae0)
Location: drivers/clk/clk.c:2850
Inline: False
```
**Symbols:**

```
ffffffff81543980-ffffffff815439a6: devm_clk_match (STB_LOCAL)
ffffffff81544ae0-ffffffff81544aff: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815a6a90)
Location: drivers/clk/clk-devres.c:73
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815a7c40)
Location: drivers/clk/clk.c:2990
Inline: False
```
**Symbols:**

```
ffffffff815a6a90-ffffffff815a6ab6: devm_clk_match (STB_LOCAL)
ffffffff815a7c40-ffffffff815a7c5e: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815de640)
Location: drivers/clk/clk-devres.c:73
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815df530)
Location: drivers/clk/clk.c:3253
Inline: False
```
**Symbols:**

```
ffffffff815de640-ffffffff815de665: devm_clk_match (STB_LOCAL)
ffffffff815df530-ffffffff815df54e: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815f7ef0)
Location: drivers/clk/clk-devres.c:92
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815f8ff0)
Location: drivers/clk/clk.c:3554
Inline: False
```
**Symbols:**

```
ffffffff815f7ef0-ffffffff815f7f15: devm_clk_match (STB_LOCAL)
ffffffff815f8ff0-ffffffff815f900e: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81629f60)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3898
Inline: False
```
**Symbols:**

```
ffffffff81629f20-ffffffff81629f4d: devm_clk_match (STB_LOCAL)
ffffffff81629f60-ffffffff81629f76: devm_clk_match.cold (STB_LOCAL)
ffffffff8162b840-ffffffff8162b85c: devm_clk_match (STB_LOCAL)
ffffffff81630e64-ffffffff81630e79: devm_clk_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff8164b9e0)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8164d260)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffff8164b9e0-ffffffff8164ba0c: devm_clk_match (STB_LOCAL)
ffffffff8164d260-ffffffff8164d27f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816faae0)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fc070)
Location: drivers/clk/clk.c:4104
Inline: False
```
**Symbols:**

```
ffffffff816faae0-ffffffff816fab07: devm_clk_match (STB_LOCAL)
ffffffff816fc070-ffffffff816fc08f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81717490)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81718f70)
Location: drivers/clk/clk.c:4173
Inline: False
```
**Symbols:**

```
ffffffff81717490-ffffffff817174b7: devm_clk_match (STB_LOCAL)
ffffffff81718f70-ffffffff81718f8f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816f8780)
Location: drivers/clk/clk-devres.c:126
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fa270)
Location: drivers/clk/clk.c:4182
Inline: False
```
**Symbols:**

```
ffffffff816f8780-ffffffff816f87a7: devm_clk_match (STB_LOCAL)
ffffffff816fa270-ffffffff816fa28f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81772f70)
Location: drivers/clk/clk-devres.c:126
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81774920)
Location: drivers/clk/clk.c:4209
Inline: False
```
**Symbols:**

```
ffffffff81772f70-ffffffff81772f97: devm_clk_match (STB_LOCAL)
ffffffff81774920-ffffffff8177493f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff818a83e0)
Location: drivers/clk/clk-devres.c:126
Inline: False
```
```
In drivers/clk/clk.c (ffffffff818aa1e0)
Location: drivers/clk/clk.c:4282
Inline: False
```
**Symbols:**

```
ffffffff818a83e0-ffffffff818a841b: devm_clk_match (STB_LOCAL)
ffffffff818aa1e0-ffffffff818aa20f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff819f2810)
Location: drivers/clk/clk-devres.c:185
Inline: False
```
**Symbols:**

```
ffffffff819f2810-ffffffff819f284b: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a3aea0)
Location: drivers/clk/clk-devres.c:185
Inline: False
```
**Symbols:**

```
ffffffff81a3aea0-ffffffff81a3aedb: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a86760)
Location: drivers/clk/clk-devres.c:185
Inline: False
```
**Symbols:**

```
ffffffff81a86760-ffffffff81a8679b: devm_clk_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffff8000107ba200)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffff8000107bc050)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffff8000107ba200-ffff8000107ba248: devm_clk_match (STB_LOCAL)
ffff8000107bc050-ffff8000107bc098: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (c08e64ac)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (c08e84f4)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
c08e64ac-c08e6504: devm_clk_match (STB_LOCAL)
c08e84f4-c08e8540: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffe0005093c6)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffe00050afe2)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffe00050afe2-ffffffe00050b024: devm_clk_match (STB_LOCAL)
ffffffe0005093c6-ffffffe000509404: devm_clk_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81611a40)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816132c0)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffff81611a40-ffffffff81611a6c: devm_clk_match (STB_LOCAL)
ffffffff816132c0-ffffffff816132df: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81605f90)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816077f0)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffff81605f90-ffffffff81605fbc: devm_clk_match (STB_LOCAL)
ffffffff816077f0-ffffffff8160780f: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff8163f820)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816410a0)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffff8163f820-ffffffff8163f84c: devm_clk_match (STB_LOCAL)
ffffffff816410a0-ffffffff816410bf: devm_clk_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int devm_clk_match(struct device *dev, void *res, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81659b70)
Location: drivers/clk/clk-devres.c:119
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8165b420)
Location: drivers/clk/clk.c:4009
Inline: False
```
**Symbols:**

```
ffffffff81659b70-ffffffff81659b9c: devm_clk_match (STB_LOCAL)
ffffffff8165b420-ffffffff8165b43f: devm_clk_match (STB_LOCAL)
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
