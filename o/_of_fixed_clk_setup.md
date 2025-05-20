# Function: <code>_of_fixed_clk_setup</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct clk *_of_fixed_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffff8000107c5288)
Location: drivers/clk/clk-fixed-rate.c:158
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_setup
```
**Symbols:**

```
ffff8000107c5288-ffff8000107c539c: _of_fixed_clk_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *_of_fixed_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (c08f099c)
Location: drivers/clk/clk-fixed-rate.c:158
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_setup
```
**Symbols:**

```
c08f099c-c08f0abc: _of_fixed_clk_setup (STB_LOCAL)
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
struct clk *_of_fixed_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffe000512734)
Location: drivers/clk/clk-fixed-rate.c:158
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_setup
```
**Symbols:**

```
ffffffe000512734-ffffffe000512810: _of_fixed_clk_setup (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
