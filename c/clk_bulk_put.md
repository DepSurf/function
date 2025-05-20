# Function: <code>clk_bulk_put</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543ab2)
Location: drivers/clk/clk-bulk.c:23
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff815439e0-ffffffff81543a2b: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6bc2)
Location: drivers/clk/clk-bulk.c:23
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff815a6af0-ffffffff815a6b3b: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815de6a0)
Location: drivers/clk/clk-bulk.c:23
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff815de6a0-ffffffff815de6ea: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815f7f60)
Location: drivers/clk/clk-bulk.c:69
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff815f7f60-ffffffff815f7faa: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8162a078)
Location: drivers/clk/clk-bulk.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81629f90-ffffffff81629fda: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8164bb38)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff8164ba50-ffffffff8164ba9a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816fae08)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff816fab50-ffffffff816fab9a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff817177b8)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81717500-ffffffff8171754a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816f8aa8)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff816f87f0-ffffffff816f883a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81773268)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81772fb0-ffffffff81772ffa: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff818a8a0f)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff818a8810-ffffffff818a886e: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f356f)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff819f3260-ffffffff819f32be: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3bbff)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81a3b8f0-ffffffff81a3b94e: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a874bf)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81a871b0-ffffffff81a8720e: clk_bulk_put (STB_GLOBAL)
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
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107baa38)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
**Symbols:**

```
ffff8000107ba410-ffff8000107ba46c: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e6aa8)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
**Symbols:**

```
c08e661c-c08e6660: clk_bulk_put (STB_GLOBAL)
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
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe000509b14)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffe00050956a-ffffffe0005095ce: clk_bulk_put (STB_GLOBAL)
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
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81611b98)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81611ab0-ffffffff81611afa: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816060e8)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81606000-ffffffff8160604a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8163f978)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff8163f890-ffffffff8163f8da: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_put(int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81659cc8)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:__clk_bulk_get
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_release
```
**Symbols:**

```
ffffffff81659be0-ffffffff81659c2a: clk_bulk_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
