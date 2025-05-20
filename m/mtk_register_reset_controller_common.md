# Function: <code>mtk_register_reset_controller_common</code>

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
void mtk_register_reset_controller_common(struct device_node *np, unsigned int num_regs, int regofs, const struct reset_control_ops *reset_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/reset.c (ffff8000107e3180)
Location: drivers/clk/mediatek/reset.c:93
Inline: False
Direct callers:
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_set_clr
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller
```
**Symbols:**

```
ffff8000107e3180-ffff8000107e3248: mtk_register_reset_controller_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mtk_register_reset_controller_common(struct device_node *np, unsigned int num_regs, int regofs, const struct reset_control_ops *reset_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/reset.c (c09002e4)
Location: drivers/clk/mediatek/reset.c:93
Inline: False
Direct callers:
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_set_clr
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller
```
**Symbols:**

```
c09002e4-c090039c: mtk_register_reset_controller_common (STB_LOCAL)
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
