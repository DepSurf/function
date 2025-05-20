# Function: <code>omap_i2c_xfer_data</code>

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
int omap_i2c_xfer_data(struct omap_i2c_dev *omap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-omap.c (ffff800010abbd88)
Location: drivers/i2c/busses/i2c-omap.c:1069
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr_thread
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
**Symbols:**

```
ffff800010abbd88-ffff800010abc12c: omap_i2c_xfer_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int omap_i2c_xfer_data(struct omap_i2c_dev *omap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-omap.c (c0b9d39c)
Location: drivers/i2c/busses/i2c-omap.c:1069
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr_thread
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
**Symbols:**

```
c0b9d39c-c0b9d748: omap_i2c_xfer_data (STB_LOCAL)
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
