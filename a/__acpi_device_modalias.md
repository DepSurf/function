# Function: <code>__acpi_device_modalias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __acpi_device_modalias(struct acpi_device *adev, char *buf, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8147bf10)
Location: drivers/acpi/device_sysfs.c:290
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff8147bf10-ffffffff8147bfad: __acpi_device_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __acpi_device_modalias(struct acpi_device *adev, char *buf, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ca5e6)
Location: drivers/acpi/device_sysfs.c:290
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff814ca5e6-ffffffff814ca67b: __acpi_device_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __acpi_device_modalias(struct acpi_device *adev, char *buf, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ec502)
Location: drivers/acpi/device_sysfs.c:290
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff814ec502-ffffffff814ec597: __acpi_device_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814f9485)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff814f93a0-ffffffff814f9426: __acpi_device_modalias.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8153ad15)
Location: drivers/acpi/device_sysfs.c:294
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff8153ac10-ffffffff8153acb7: __acpi_device_modalias.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81570b85)
Location: drivers/acpi/device_sysfs.c:294
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff81570a80-ffffffff81570b27: __acpi_device_modalias.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81588705)
Location: drivers/acpi/device_sysfs.c:298
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff81588650-ffffffff815886f7: __acpi_device_modalias.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b93d5)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815b9310-ffffffff815b93c1: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815da615)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815da550-ffffffff815da601: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81684935)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff81684830-ffffffff816848d3: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816a2605)
Location: drivers/acpi/device_sysfs.c:282
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff816a2500-ffffffff816a25a3: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816853f5)
Location: drivers/acpi/device_sysfs.c:283
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff816852f0-ffffffff81685393: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816fa6b5)
Location: drivers/acpi/device_sysfs.c:285
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff816fa5b0-ffffffff816fa653: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81827af5)
Location: drivers/acpi/device_sysfs.c:286
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff818279d0-ffffffff81827a90: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81959af5)
Location: drivers/acpi/device_sysfs.c:286
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff819599b0-ffffffff81959a70: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8199ff55)
Location: drivers/acpi/device_sysfs.c:286
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff8199fe10-ffffffff8199fed0: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff819e85c5)
Location: drivers/acpi/device_sysfs.c:284
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff819e8480-ffffffff819e8540: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
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
In drivers/acpi/device_sysfs.c (ffff800010766b3c)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffff800010766a38-ffff800010766b20: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815ccde5)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815ccd20-ffffffff815ccdd1: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b6965)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815b68a0-ffffffff815b6951: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815ce8f5)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815ce830-ffffffff815ce8e1: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815e87b5)
Location: drivers/acpi/device_sysfs.c:290
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_modalias_show
  - drivers/acpi/device_sysfs.c:acpi_device_modalias
```
**Symbols:**

```
ffffffff815e86f0-ffffffff815e87a1: __acpi_device_modalias.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
