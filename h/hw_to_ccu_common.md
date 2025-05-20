# Function: <code>hw_to_ccu_common</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4ca8)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_get_mmc_timing_mode
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5034)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_parent
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_get_parent
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_determine_rate
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_recalc_rate
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_is_enabled
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_enable
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_disable
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f59d4)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_round_rate
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_recalc_rate
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_is_enabled
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_enable
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_disable
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f5fac)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_set_parent
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_get_parent
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_is_enabled
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_enable
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_disable
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f6764)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_parent
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_get_parent
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_determine_rate
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_is_enabled
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_enable
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_disable
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6b68)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_get_phase
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f76fc)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_round_rate
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_recalc_rate
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_is_enabled
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_enable
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_disable
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7ccc)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_parent
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_get_parent
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_determine_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_recalc_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_is_enabled
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_enable
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_disable
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f8500)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_round_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_recalc_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_is_enabled
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_enable
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_disable
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f8d28)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_round_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_recalc_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_is_enabled
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_enable
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_disable
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f978c)
Location: drivers/clk/sunxi-ng/ccu_common.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_set_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_parent
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_get_parent
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_is_enabled
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_enable
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_disable
```
</details>
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
