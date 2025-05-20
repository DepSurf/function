# Function: <code>path_show</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff817deaa0)
Location: drivers/pps/sysfs.c:87
Inline: False
```
**Symbols:**

```
ffffffff817deaa0-ffffffff817deaca: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff81809ed0)
Location: drivers/pps/sysfs.c:87
Inline: False
```
**Symbols:**

```
ffffffff81809ed0-ffffffff81809efa: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff8184bb80)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff8184bb80-ffffffff8184bba7: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff8187d390)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff8187d390-ffffffff8187d3b7: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff8194b760)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff8194b760-ffffffff8194b787: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff81951170)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81951170-ffffffff81951197: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81685440)
Location: drivers/acpi/device_sysfs.c:423
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81934ff0)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81685440-ffffffff816854ca: path_show (STB_LOCAL)
ffffffff81934ff0-ffffffff81935017: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816fa700)
Location: drivers/acpi/device_sysfs.c:428
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff819d8410)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff816fa700-ffffffff816fa78a: path_show (STB_LOCAL)
ffffffff819d8410-ffffffff819d8437: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81827b60)
Location: drivers/acpi/device_sysfs.c:429
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81b3b7d0)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81827b60-ffffffff81827bef: path_show (STB_LOCAL)
ffffffff81b3b7d0-ffffffff81b3b801: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81959b70)
Location: drivers/acpi/device_sysfs.c:429
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81cd1620)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81959b70-ffffffff81959bff: path_show (STB_LOCAL)
ffffffff81cd1620-ffffffff81cd1651: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8199ffd0)
Location: drivers/acpi/device_sysfs.c:429
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81d39060)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff8199ffd0-ffffffff819a005f: path_show (STB_LOCAL)
ffffffff81d39060-ffffffff81d39091: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff819e8640)
Location: drivers/acpi/device_sysfs.c:427
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81def300)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff819e8640-ffffffff819e86cf: path_show (STB_LOCAL)
ffffffff81def300-ffffffff81def331: path_show (STB_LOCAL)
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
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffff800010ac6b20)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffff800010ac6b20-ffff800010ac6b64: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (c0ba666c)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
c0ba666c-c0ba669c: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (c000000000ba8190)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
c000000000ba8190-c000000000ba81d8: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffe0006c561e)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffe0006c561e-ffffffe0006c565e: path_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff81825900)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81825900-ffffffff81825927: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff817ecf90)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff817ecf90-ffffffff817ecfb7: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff81872840)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff81872840-ffffffff81872867: path_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t path_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/sysfs.c (ffffffff8188e1f0)
Location: drivers/pps/sysfs.c:73
Inline: False
```
**Symbols:**

```
ffffffff8188e1f0-ffffffff8188e217: path_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
