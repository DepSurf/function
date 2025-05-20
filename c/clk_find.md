# Function: <code>clk_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816e3d08)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81748048)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff815308b8)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81543d88)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff815a6e98)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff815dea3b)
Location: drivers/clk/clkdev.c:135
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff815f836b)
Location: drivers/clk/clkdev.c:132
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get_sys
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a3e0)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff8162a3e0-ffffffff8162a4b3: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164bea0)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff8164bea0-ffffffff8164bf73: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816faf20)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff816faf20-ffffffff816faff3: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717870)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81717870-ffffffff81717943: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f8b60)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff816f8b60-ffffffff816f8c37: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773320)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81773320-ffffffff817733f7: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a8be0)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff818a8be0-ffffffff818a8cc1: clk_find (STB_LOCAL)
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
In drivers/clk/clkdev.c (ffffffff819f3cfb)
Location: drivers/clk/clkdev.c:36
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_find_hw
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
In drivers/clk/clkdev.c (ffffffff81a3c3a8)
Location: drivers/clk/clkdev.c:36
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_find_hw
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
In drivers/clk/clkdev.c (ffffffff81a87c68)
Location: drivers/clk/clkdev.c:36
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_find_hw
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
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bab00)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffff8000107bab00-ffff8000107babe8: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e6b50)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
c08e6b50-c08e6c3c: clk_find (STB_LOCAL)
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
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe000509bc8)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffe000509bc8-ffffffe000509c76: clk_find (STB_LOCAL)
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
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81611f00)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff81611f00-ffffffff81611fd3: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606450)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff81606450-ffffffff81606523: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8163fce0)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff8163fce0-ffffffff8163fdb3: clk_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_lookup *clk_find(const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a030)
Location: drivers/clk/clkdev.c:36
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_find_hw
```
**Symbols:**

```
ffffffff8165a030-ffffffff8165a103: clk_find (STB_LOCAL)
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
