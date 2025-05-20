# Function: <code>of_platform_depopulate</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void of_platform_depopulate(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6d558)
Location: drivers/of/platform.c:576
Inline: True
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_remove
  - drivers/firmware/ti_sci.c:ti_sci_remove
  - drivers/of/platform.c:devm_of_platform_populate_release
```
**Symbols:**

```
ffff800010b6d558-ffff800010b6d5e0: of_platform_depopulate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void of_platform_depopulate(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c501b4)
Location: drivers/of/platform.c:576
Inline: True
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove_dt
  - drivers/of/platform.c:devm_of_platform_populate_release
```
**Symbols:**

```
c0c501b4-c0c50208: of_platform_depopulate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void of_platform_depopulate(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c47860)
Location: drivers/of/platform.c:576
Inline: True
Direct callers:
  - drivers/of/platform.c:devm_of_platform_populate_release
```
**Symbols:**

```
c000000000c47860-c000000000c478e0: of_platform_depopulate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void of_platform_depopulate(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe000721f3c)
Location: drivers/of/platform.c:576
Inline: True
Direct callers:
  - drivers/of/platform.c:devm_of_platform_populate_release
```
**Symbols:**

```
ffffffe000721f3c-ffffffe000721f96: of_platform_depopulate (STB_GLOBAL)
```
</details>
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
