# Function: <code>soc_device_to_device</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *soc_device_to_device(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81b78730)
Location: drivers/base/soc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81b78730-ffffffff81b78744: soc_device_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *soc_device_to_device(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81bcc600)
Location: drivers/base/soc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81bcc600-ffffffff81bcc614: soc_device_to_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device *soc_device_to_device(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffff80001091ebe0)
Location: drivers/base/soc.c:40
Inline: False
Direct callers:
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
```
**Symbols:**

```
ffff80001091ebe0-ffff80001091ec08: soc_device_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *soc_device_to_device(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0a03ef4)
Location: drivers/base/soc.c:40
Inline: False
Direct callers:
  - arch/arm/mach-imx/cpu.c:imx_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_soc_device_register
```
**Symbols:**

```
c0a03ef4-c0a03f0c: soc_device_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *soc_device_to_device(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0000000009c3ce0)
Location: drivers/base/soc.c:40
Inline: False
```
**Symbols:**

```
c0000000009c3ce0-c0000000009c3cec: soc_device_to_device (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
