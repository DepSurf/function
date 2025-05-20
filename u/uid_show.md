# Function: <code>uid_show</code>

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
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81684cc0)
Location: drivers/acpi/device_sysfs.c:402
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81691d70)
Location: drivers/acpi/dock.c:535
Inline: False
```
**Symbols:**

```
ffffffff81684cc0-ffffffff81684ce6: uid_show (STB_LOCAL)
ffffffff81691d70-ffffffff81691de6: uid_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816f9f80)
Location: drivers/acpi/device_sysfs.c:407
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81707880)
Location: drivers/acpi/dock.c:535
Inline: False
```
**Symbols:**

```
ffffffff816f9f80-ffffffff816f9fa6: uid_show (STB_LOCAL)
ffffffff81707880-ffffffff817078f6: uid_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81827300)
Location: drivers/acpi/device_sysfs.c:408
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81835c50)
Location: drivers/acpi/dock.c:534
Inline: False
```
**Symbols:**

```
ffffffff81827300-ffffffff81827330: uid_show (STB_LOCAL)
ffffffff81835c50-ffffffff81835cd4: uid_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81959220)
Location: drivers/acpi/device_sysfs.c:408
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81969c10)
Location: drivers/acpi/dock.c:534
Inline: False
```
**Symbols:**

```
ffffffff81959220-ffffffff81959250: uid_show (STB_LOCAL)
ffffffff81969c10-ffffffff81969c94: uid_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8199f680)
Location: drivers/acpi/device_sysfs.c:408
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff819b01d0)
Location: drivers/acpi/dock.c:534
Inline: False
```
**Symbols:**

```
ffffffff8199f680-ffffffff8199f6b0: uid_show (STB_LOCAL)
ffffffff819b01d0-ffffffff819b0254: uid_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t uid_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff819e7d00)
Location: drivers/acpi/device_sysfs.c:406
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff819fa680)
Location: drivers/acpi/dock.c:534
Inline: False
```
**Symbols:**

```
ffffffff819e7d00-ffffffff819e7d30: uid_show (STB_LOCAL)
ffffffff819fa680-ffffffff819fa704: uid_show (STB_LOCAL)
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
