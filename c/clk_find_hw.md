# Function: <code>clk_find_hw</code>

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
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a9c0)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff8162a9c0-ffffffff8162aa0f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c490)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff8164c490-ffffffff8164c4df: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb4f8)
Location: drivers/clk/clkdev.c:72
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff816fb680-ffffffff816fb6cf: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717e48)
Location: drivers/clk/clkdev.c:72
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81717fd0-ffffffff8171801f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f9138)
Location: drivers/clk/clkdev.c:72
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff816f92c0-ffffffff816f930f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773898)
Location: drivers/clk/clkdev.c:72
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81773a20-ffffffff81773a6f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a91f7)
Location: drivers/clk/clkdev.c:72
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff818a93d0-ffffffff818a9425: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3cd0)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff819f3cd0-ffffffff819f3ddb: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c380)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81a3c380-ffffffff81a3c498: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87c40)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81a87c40-ffffffff81a87d58: clk_find_hw (STB_GLOBAL)
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
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bb210)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffff8000107bb210-ffff8000107bb274: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e70d8)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
c08e70d8-c08e712c: clk_find_hw (STB_GLOBAL)
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
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe00050a0c6)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffe00050a0c6-ffffffe00050a120: clk_find_hw (STB_GLOBAL)
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
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816124f0)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff816124f0-ffffffff8161253f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606a40)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff81606a40-ffffffff81606a8f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816402d0)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff816402d0-ffffffff8164031f: clk_find_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_find_hw(const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a620)
Location: drivers/clk/clkdev.c:72
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffff8165a620-ffffffff8165a66f: clk_find_hw (STB_GLOBAL)
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
