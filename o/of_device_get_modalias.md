# Function: <code>of_device_get_modalias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:75
Inline: True
```
</details>
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
ssize_t of_device_get_modalias(struct device *dev, char *str, ssize_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffff800010b6cae8)
Location: drivers/of/device.c:200
Inline: False
Direct callers:
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_modalias
  - drivers/of/device.c:of_device_request_module
  - drivers/of/device.c:of_device_request_module
```
**Symbols:**

```
ffff800010b6cae8-ffff800010b6cc48: of_device_get_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t of_device_get_modalias(struct device *dev, char *str, ssize_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c0c4fb44)
Location: drivers/of/device.c:200
Inline: False
Direct callers:
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_modalias
  - drivers/of/device.c:of_device_request_module
  - drivers/of/device.c:of_device_request_module
```
**Symbols:**

```
c0c4fb44-c0c4fc84: of_device_get_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t of_device_get_modalias(struct device *dev, char *str, ssize_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c000000000c47010)
Location: drivers/of/device.c:200
Inline: False
Direct callers:
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_modalias
  - drivers/of/device.c:of_device_request_module
  - drivers/of/device.c:of_device_request_module
```
**Symbols:**

```
c000000000c47010-c000000000c47204: of_device_get_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t of_device_get_modalias(struct device *dev, char *str, ssize_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffffffe00072177c)
Location: drivers/of/device.c:200
Inline: False
Direct callers:
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_modalias
  - drivers/of/device.c:of_device_request_module
  - drivers/of/device.c:of_device_request_module
```
**Symbols:**

```
ffffffe00072177c-ffffffe0007218a4: of_device_get_modalias (STB_LOCAL)
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
