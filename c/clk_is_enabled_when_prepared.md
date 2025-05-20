# Function: <code>clk_is_enabled_when_prepared</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816f9c40)
Location: drivers/clk/clk.c:1182
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff816f9c40-ffffffff816f9c6d: clk_is_enabled_when_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817743a0)
Location: drivers/clk/clk.c:1182
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff817743a0-ffffffff817743cd: clk_is_enabled_when_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818a9e90)
Location: drivers/clk/clk.c:1194
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff818a9e90-ffffffff818a9ec5: clk_is_enabled_when_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f4ce0)
Location: drivers/clk/clk.c:1278
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff819f4ce0-ffffffff819f4d15: clk_is_enabled_when_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3d440)
Location: drivers/clk/clk.c:1320
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff81a3d440-ffffffff81a3d475: clk_is_enabled_when_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool clk_is_enabled_when_prepared(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a88d00)
Location: drivers/clk/clk.c:1320
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff81a88d00-ffffffff81a88d35: clk_is_enabled_when_prepared (STB_GLOBAL)
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
