# Function: <code>ar8031_phy_fixup</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int ar8031_phy_fixup(struct phy_device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-imx/mach-imx6q.c (c0333b7c)
Location: arch/arm/mach-imx/mach-imx6q.c:105
Inline: False
Direct callers:
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
```
```
In arch/arm/mach-imx/mach-imx6sx.c (c0333f1c)
Location: arch/arm/mach-imx/mach-imx6sx.c:18
Inline: False
```
```
In arch/arm/mach-imx/mach-imx7d.c (c03340a8)
Location: arch/arm/mach-imx/mach-imx7d.c:17
Inline: False
```
**Symbols:**

```
c0333b7c-c0333c40: ar8031_phy_fixup (STB_LOCAL)
c0333f1c-c0333fa0: ar8031_phy_fixup (STB_LOCAL)
c03340a8-c0334154: ar8031_phy_fixup (STB_LOCAL)
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
