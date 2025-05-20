# Function: <code>__spi_add_device</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:596
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff818fc0d0-ffffffff818fc1ba: __spi_add_device (STB_LOCAL)
ffffffff81d0fbde-ffffffff81d0fc78: __spi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:565
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81a4d780-ffffffff81a4d855: __spi_add_device (STB_LOCAL)
ffffffff81eda90c-ffffffff81eda9a3: __spi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7b90)
Location: drivers/spi/spi.c:627
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81bd7b90-ffffffff81bd7d1d: __spi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2e5b0)
Location: drivers/spi/spi.c:628
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81c2e5b0-ffffffff81c2e750: __spi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce1000)
Location: drivers/spi/spi.c:639
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81ce1000-ffffffff81ce1331: __spi_add_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
