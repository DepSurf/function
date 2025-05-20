# Function: <code>owl_gate_clk_is_enabled</code>

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
int owl_gate_clk_is_enabled(const struct owl_clk_common *common, const struct owl_gate_hw *gate_hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-gate.c (ffff8000107c9c50)
Location: drivers/clk/actions/owl-gate.c:52
Inline: False
Direct callers:
  - drivers/clk/actions/owl-gate.c:owl_gate_is_enabled
  - drivers/clk/actions/owl-composite.c:owl_comp_is_enabled
```
**Symbols:**

```
ffff8000107c9c50-ffff8000107c9ce8: owl_gate_clk_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int owl_gate_clk_is_enabled(const struct owl_clk_common *common, const struct owl_gate_hw *gate_hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-gate.c (c08f5a98)
Location: drivers/clk/actions/owl-gate.c:52
Inline: False
Direct callers:
  - drivers/clk/actions/owl-gate.c:owl_gate_is_enabled
  - drivers/clk/actions/owl-composite.c:owl_comp_is_enabled
```
**Symbols:**

```
c08f5a98-c08f5b20: owl_gate_clk_is_enabled (STB_GLOBAL)
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
