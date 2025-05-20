# Function: <code>hi6220_clk_register_divider</code>

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
void hi6220_clk_register_divider(const struct hi6220_divider_clock *clks, int nums, struct hisi_clock_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clk.c (ffff8000114853e0)
Location: drivers/clk/hisilicon/clk.c:316
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver
```
**Symbols:**

```
ffff8000114853e0-ffff8000114854c4: hi6220_clk_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hi6220_clk_register_divider(const struct hi6220_divider_clock *clks, int nums, struct hisi_clock_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clk.c (c155750c)
Location: drivers/clk/hisilicon/clk.c:316
Inline: False
Direct callers:
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver
```
**Symbols:**

```
c155750c-c15575f4: hi6220_clk_register_divider (STB_GLOBAL)
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
