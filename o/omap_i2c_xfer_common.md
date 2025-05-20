# Function: <code>omap_i2c_xfer_common</code>

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
int omap_i2c_xfer_common(struct i2c_adapter *adap, struct i2c_msg *msgs, int num, bool polling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-omap.c (ffff800010abc540)
Location: drivers/i2c/busses/i2c-omap.c:792
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_polling
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_irq
```
**Symbols:**

```
ffff800010abc540-ffff800010abc754: omap_i2c_xfer_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int omap_i2c_xfer_common(struct i2c_adapter *adap, struct i2c_msg *msgs, int num, bool polling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-omap.c (c0b9db64)
Location: drivers/i2c/busses/i2c-omap.c:792
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_polling
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_irq
```
**Symbols:**

```
c0b9db64-c0b9dd8c: omap_i2c_xfer_common (STB_LOCAL)
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
