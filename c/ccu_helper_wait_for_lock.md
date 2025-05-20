# Function: <code>ccu_helper_wait_for_lock</code>

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
void ccu_helper_wait_for_lock(struct ccu_common *common, u32 lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/sunxi-ng/ccu_common.c (ffff8000107f4820)
Location: drivers/clk/sunxi-ng/ccu_common.c:19
Inline: True
Direct callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
```
**Symbols:**

```
ffff8000107f4820-ffff8000107f48bc: ccu_helper_wait_for_lock.part.0 (STB_LOCAL)
ffff8000107f4940-ffff8000107f4978: ccu_helper_wait_for_lock (STB_GLOBAL)
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
