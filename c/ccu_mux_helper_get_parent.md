# Function: <code>ccu_mux_helper_get_parent</code>

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
u8 ccu_mux_helper_get_parent(struct ccu_common *common, struct ccu_mux_internal *cm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f6328)
Location: drivers/clk/sunxi-ng/ccu_mux.c:156
Inline: False
Direct callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_get_parent
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_get_parent
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_get_parent
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_get_parent
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_get_parent
```
**Symbols:**

```
ffff8000107f6328-ffff8000107f63dc: ccu_mux_helper_get_parent (STB_GLOBAL)
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
