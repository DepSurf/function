# Function: <code>params_from_rate</code>

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
void params_from_rate(long unsigned int requested_rate, long unsigned int parent_rate, unsigned int *sdm, unsigned int *n2, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/meson/clk-mpll.c (ffff8000107e69e8)
Location: drivers/clk/meson/clk-mpll.c:43
Inline: False
Direct callers:
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-mpll.c:mpll_round_rate
```
**Symbols:**

```
ffff8000107e69e8-ffff8000107e6ad0: params_from_rate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void params_from_rate(long unsigned int requested_rate, long unsigned int parent_rate, unsigned int *sdm, unsigned int *n2, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/meson/clk-mpll.c (c0901ce8)
Location: drivers/clk/meson/clk-mpll.c:43
Inline: False
Direct callers:
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-mpll.c:mpll_round_rate
```
**Symbols:**

```
c0901ce8-c0901e30: params_from_rate (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
