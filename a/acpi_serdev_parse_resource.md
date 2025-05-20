# Function: <code>acpi_serdev_parse_resource</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176df40)
Location: drivers/tty/serdev/core.c:567
Inline: True
```
**Symbols:**

```
ffffffff8176df40-ffffffff8176df89: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788900)
Location: drivers/tty/serdev/core.c:567
Inline: True
```
**Symbols:**

```
ffffffff81788900-ffffffff81788949: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176c250)
Location: drivers/tty/serdev/core.c:567
Inline: True
```
**Symbols:**

```
ffffffff8176c250-ffffffff8176c299: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f17d0)
Location: drivers/tty/serdev/core.c:592
Inline: False
```
**Symbols:**

```
ffffffff817f17d0-ffffffff817f1819: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81931e90)
Location: drivers/tty/serdev/core.c:592
Inline: False
```
**Symbols:**

```
ffffffff81931e90-ffffffff81931ef1: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a908d0)
Location: drivers/tty/serdev/core.c:592
Inline: False
```
**Symbols:**

```
ffffffff81a908d0-ffffffff81a90931: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adc0e0)
Location: drivers/tty/serdev/core.c:603
Inline: False
```
**Symbols:**

```
ffffffff81adc0e0-ffffffff81adc141: acpi_serdev_parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_serdev_parse_resource(struct acpi_resource *ares, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2f3c0)
Location: drivers/tty/serdev/core.c:596
Inline: False
```
**Symbols:**

```
ffffffff81b2f3c0-ffffffff81b2f421: acpi_serdev_parse_resource (STB_LOCAL)
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
