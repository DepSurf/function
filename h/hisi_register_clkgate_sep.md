# Function: <code>hisi_register_clkgate_sep</code>

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
struct clk *hisi_register_clkgate_sep(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d03b8)
Location: drivers/clk/hisilicon/clkgate-separated.c:83
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate_sep
```
**Symbols:**

```
ffff8000107d03b8-ffff8000107d04cc: hisi_register_clkgate_sep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *hisi_register_clkgate_sep(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clkgate-separated.c (c08f7d0c)
Location: drivers/clk/hisilicon/clkgate-separated.c:83
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate_sep
```
**Symbols:**

```
c08f7d0c-c08f7e20: hisi_register_clkgate_sep (STB_GLOBAL)
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
