# Function: <code>of_device_add</code>

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
int of_device_add(struct platform_device *ofdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffff800010b6cdf0)
Location: drivers/of/device.c:56
Inline: True
Direct callers:
  - drivers/of/device.c:of_device_register
  - drivers/of/platform.c:of_platform_device_create_pdata
```
**Symbols:**

```
ffff800010b6cdf0-ffff800010b6ce50: of_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_device_add(struct platform_device *ofdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c0c4fdec)
Location: drivers/of/device.c:56
Inline: True
Direct callers:
  - drivers/of/device.c:of_device_register
  - drivers/of/platform.c:of_platform_device_create_pdata
```
**Symbols:**

```
c0c4fdec-c0c4fe38: of_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_device_add(struct platform_device *ofdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c000000000c47480)
Location: drivers/of/device.c:56
Inline: False
Direct callers:
  - drivers/of/device.c:of_device_register
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/platform.c:of_platform_device_create_pdata
```
**Symbols:**

```
c000000000c47480-c000000000c47500: of_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_device_add(struct platform_device *ofdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffffffe000721c7c)
Location: drivers/of/device.c:56
Inline: True
Direct callers:
  - drivers/of/device.c:of_device_register
  - drivers/of/platform.c:of_platform_device_create_pdata
```
**Symbols:**

```
ffffffe000721c7c-ffffffe000721cbe: of_device_add (STB_GLOBAL)
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
