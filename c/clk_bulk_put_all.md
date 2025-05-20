# Function: <code>clk_bulk_put_all</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815f8210)
Location: drivers/clk/clk-bulk.c:108
Inline: True
```
**Symbols:**

```
ffffffff815f8210-ffffffff815f8277: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8162a270)
Location: drivers/clk/clk-bulk.c:125
Inline: True
```
**Symbols:**

```
ffffffff8162a270-ffffffff8162a2d7: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8164bd30)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff8164bd30-ffffffff8164bd97: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816fad00)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff816fad00-ffffffff816fad67: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff817176b0)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff817176b0-ffffffff81717717: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816f89a0)
Location: drivers/clk/clk-bulk.c:128
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff816f89a0-ffffffff816f8a07: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81773160)
Location: drivers/clk/clk-bulk.c:128
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff81773160-ffffffff817731c7: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff818a89f0)
Location: drivers/clk/clk-bulk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff818a89f0-ffffffff818a8a6b: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f3550)
Location: drivers/clk/clk-bulk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff819f3550-ffffffff819f35cb: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3bbe0)
Location: drivers/clk/clk-bulk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff81a3bbe0-ffffffff81a3bc5b: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a874a0)
Location: drivers/clk/clk-bulk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release_all
```
**Symbols:**

```
ffffffff81a874a0-ffffffff81a8751b: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba860)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffff8000107ba860-ffff8000107ba8d8: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e6914)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
c08e6914-c08e696c: clk_bulk_put_all (STB_GLOBAL)
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
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe00050998e)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffe00050998e-ffffffe000509a0a: clk_bulk_put_all (STB_GLOBAL)
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
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81611d90)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff81611d90-ffffffff81611df7: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816062e0)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff816062e0-ffffffff81606347: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8163fb70)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff8163fb70-ffffffff8163fbd7: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put_all(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81659ec0)
Location: drivers/clk/clk-bulk.c:128
Inline: True
```
**Symbols:**

```
ffffffff81659ec0-ffffffff81659f27: clk_bulk_put_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
