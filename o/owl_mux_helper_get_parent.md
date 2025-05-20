# Function: <code>owl_mux_helper_get_parent</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u8 owl_mux_helper_get_parent(const struct owl_clk_common *common, const struct owl_mux_hw *mux_hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-mux.c (ffff8000107c9d40)
Location: drivers/clk/actions/owl-mux.c:16
Inline: True
Inline callers:
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
Direct callers:
  - drivers/clk/actions/owl-composite.c:owl_comp_get_parent
```
**Symbols:**

```
ffff8000107c9d90-ffff8000107c9e14: owl_mux_helper_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u8 owl_mux_helper_get_parent(const struct owl_clk_common *common, const struct owl_mux_hw *mux_hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-mux.c (c08f5b80)
Location: drivers/clk/actions/owl-mux.c:16
Inline: True
Inline callers:
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
Direct callers:
  - drivers/clk/actions/owl-composite.c:owl_comp_get_parent
```
**Symbols:**

```
c08f5bc4-c08f5c44: owl_mux_helper_get_parent (STB_GLOBAL)
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
