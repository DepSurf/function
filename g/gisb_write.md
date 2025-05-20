# Function: <code>gisb_write</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/bus/brcmstb_gisb.c (ffff80001068018c)
Location: drivers/bus/brcmstb_gisb.c:128
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_resume_noirq
  - drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout
```
**Symbols:**

```
ffff80001067fe10-ffff80001067fe84: gisb_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gisb_write(struct brcmstb_gisb_arb_device *gdev, u32 val, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/bus/brcmstb_gisb.c (c0823f08)
Location: drivers/bus/brcmstb_gisb.c:128
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_resume_noirq
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout
```
**Symbols:**

```
c0823f08-c0823f74: gisb_write (STB_LOCAL)
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
