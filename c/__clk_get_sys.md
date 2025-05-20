# Function: <code>__clk_get_sys</code>

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
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162aa10)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff8162aa10-ffffffff8162aa4c: __clk_get_sys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c4e0)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff8164c4e0-ffffffff8164c51c: __clk_get_sys (STB_LOCAL)
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
In drivers/clk/clkdev.c (ffffffff816fb4f8)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81717e48)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff816f9138)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81773898)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff818a91f7)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff819f3edf)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81a3c59f)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffff81a87e5f)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffff8000107bb2f0)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (c08e7184)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
In drivers/clk/clkdev.c (ffffffe00050a168)
Location: drivers/clk/clkdev.c:86
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
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
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81612540)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81612540-ffffffff8161257c: __clk_get_sys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606a90)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81606a90-ffffffff81606acc: __clk_get_sys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81640320)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81640320-ffffffff8164035c: __clk_get_sys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk *__clk_get_sys(struct device *dev, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a670)
Location: drivers/clk/clkdev.c:86
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff8165a670-ffffffff8165a6ac: __clk_get_sys (STB_LOCAL)
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
