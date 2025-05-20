# Function: <code>clk_readl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff816e90ef)
Location: include/linux/clk-provider.h:767
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff816e9c5f)
Location: include/linux/clk-provider.h:767
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
```
```
In drivers/clk/clk-multiplier.c (ffffffff816e9e9d)
Location: include/linux/clk-provider.h:767
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffffffff816ea1a9)
Location: include/linux/clk-provider.h:767
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff816eaaf8)
Location: include/linux/clk-provider.h:767
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8174d56d)
Location: include/linux/clk-provider.h:886
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff8174e3dd)
Location: include/linux/clk-provider.h:886
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff8174e663)
Location: include/linux/clk-provider.h:886
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff8174e8f7)
Location: include/linux/clk-provider.h:886
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8174f55c)
Location: include/linux/clk-provider.h:886
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81535ddd)
Location: include/linux/clk-provider.h:898
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff81536c4d)
Location: include/linux/clk-provider.h:898
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff81536ed3)
Location: include/linux/clk-provider.h:898
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff81537167)
Location: include/linux/clk-provider.h:898
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81537dcc)
Location: include/linux/clk-provider.h:898
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81549129)
Location: include/linux/clk-provider.h:908
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff81549f9d)
Location: include/linux/clk-provider.h:908
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff8154a213)
Location: include/linux/clk-provider.h:908
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff8154a4a4)
Location: include/linux/clk-provider.h:908
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff8154b07c)
Location: include/linux/clk-provider.h:908
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff815ac665)
Location: include/linux/clk-provider.h:925
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff815ad51d)
Location: include/linux/clk-provider.h:925
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff815ad797)
Location: include/linux/clk-provider.h:925
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff815ada24)
Location: include/linux/clk-provider.h:925
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff815ae69c)
Location: include/linux/clk-provider.h:925
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff815e4772)
Location: include/linux/clk-provider.h:976
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff815e56aa)
Location: include/linux/clk-provider.h:976
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff815e5927)
Location: include/linux/clk-provider.h:976
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff815e5c03)
Location: include/linux/clk-provider.h:976
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff815e68f9)
Location: include/linux/clk-provider.h:976
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff815feb62)
Location: include/linux/clk-provider.h:1012
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffff815ffa9a)
Location: include/linux/clk-provider.h:1012
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffff815ffd17)
Location: include/linux/clk-provider.h:1012
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffff815ffff3)
Location: include/linux/clk-provider.h:1012
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81600d29)
Location: include/linux/clk-provider.h:1012
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
</details>
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
