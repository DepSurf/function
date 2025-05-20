# Function: <code>usb2_clock_sel_enable_extal_only</code>

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
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb3e8)
Location: drivers/clk/renesas/rcar-usb2-clock-sel.c:37
Inline: False
Direct callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable
```
**Symbols:**

```
ffff8000107eb3e8-ffff8000107eb494: usb2_clock_sel_enable_extal_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void usb2_clock_sel_enable_extal_only(struct usb2_clock_sel_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904a54)
Location: drivers/clk/renesas/rcar-usb2-clock-sel.c:37
Inline: True
Direct callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable
```
**Symbols:**

```
c0904a54-c0904b08: usb2_clock_sel_enable_extal_only (STB_LOCAL)
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
