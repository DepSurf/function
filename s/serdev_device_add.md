# Function: <code>serdev_device_add</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816095e0)
Location: drivers/tty/serdev/core.c:73
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff816095e0-ffffffff816096da: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81642dc0)
Location: drivers/tty/serdev/core.c:98
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81642dc0-ffffffff81642eaf: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81660ed0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81660ed0-ffffffff81660fbf: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff816973e6-ffffffff81697436: serdev_device_add.cold (STB_LOCAL)
ffffffff81696a90-ffffffff81696b35: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff816b9fb2-ffffffff816ba002: serdev_device_add.cold (STB_LOCAL)
ffffffff816b9620-ffffffff816b96c5: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff8176e3f0-ffffffff8176e441: serdev_device_add.cold (STB_LOCAL)
ffffffff8176d8b0-ffffffff8176d955: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81c083ee-ffffffff81c0843f: serdev_device_add.cold (STB_LOCAL)
ffffffff81788290-ffffffff81788335: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81bf9fb3-ffffffff81bfa004: serdev_device_add.cold (STB_LOCAL)
ffffffff8176bbe0-ffffffff8176bc85: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81cfa84e-ffffffff81cfa89f: serdev_device_add.cold (STB_LOCAL)
ffffffff817f1310-ffffffff817f13b2: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81ec2abf-ffffffff81ec2b0d: serdev_device_add.cold (STB_LOCAL)
ffffffff81931910-ffffffff819319b5: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a90210)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81a90210-ffffffff81a90311: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adba20)
Location: drivers/tty/serdev/core.c:102
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81adba20-ffffffff81adbb21: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2ed80)
Location: drivers/tty/serdev/core.c:104
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81b2ed80-ffffffff81b2ee81: serdev_device_add (STB_GLOBAL)
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
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9308)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffff8000108a9308-ffff8000108a9408: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a5bc0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
c09a5bc0-c09a5cb0: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c0000000009406b0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
c0000000009406b0-c000000000940808: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055e980)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
ffffffe00055e980-ffffffe00055ea62: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff8167fa12-ffffffff8167fa62: serdev_device_add.cold (STB_LOCAL)
ffffffff8167f080-ffffffff8167f125: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff816addf2-ffffffff816ade42: serdev_device_add.cold (STB_LOCAL)
ffffffff816ad460-ffffffff816ad505: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int serdev_device_add(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:101
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff816c8252-ffffffff816c82a2: serdev_device_add.cold (STB_LOCAL)
ffffffff816c78c0-ffffffff816c7965: serdev_device_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
