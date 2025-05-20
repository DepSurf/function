# Function: <code>hi6220_register_clkdiv</code>

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
struct clk *hi6220_register_clkdiv(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u32 mask_bit, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d0718)
Location: drivers/clk/hisilicon/clkdivider-hi6220.c:100
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider
```
**Symbols:**

```
ffff8000107d0718-ffff8000107d08b4: hi6220_register_clkdiv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *hi6220_register_clkdiv(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u32 mask_bit, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clkdivider-hi6220.c (c08f7f6c)
Location: drivers/clk/hisilicon/clkdivider-hi6220.c:100
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider
```
**Symbols:**

```
c08f7f6c-c08f8118: hi6220_register_clkdiv (STB_GLOBAL)
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
