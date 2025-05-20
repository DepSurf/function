# Function: <code>ccu_gate_helper_disable</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ccu_gate_helper_disable(struct ccu_common *common, u32 gate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5ba0)
Location: drivers/clk/sunxi-ng/ccu_gate.c:12
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_disable
Direct callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_disable
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_disable
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_disable
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_disable
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_disable
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_disable
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_disable
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_disable
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_disable
```
**Symbols:**

```
ffff8000107f5aa0-ffff8000107f5b7c: ccu_gate_helper_disable.part.0 (STB_LOCAL)
ffff8000107f5cd8-ffff8000107f5d10: ccu_gate_helper_disable (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
