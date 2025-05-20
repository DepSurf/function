# Function: <code>acpi_ec_setup</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f5a66)
Location: drivers/acpi/ec.c:1478
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff814f3f72-ffffffff814f3fcb: acpi_ec_setup.part.14 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81503e17)
Location: drivers/acpi/ec.c:1503
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81501ec0-ffffffff81501f1b: acpi_ec_setup.part.17 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81546151)
Location: drivers/acpi/ec.c:1504
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81544150-ffffffff815441aa: acpi_ec_setup.part.18 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8157b57e)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff8157a150-ffffffff8157a1aa: acpi_ec_setup.part.19 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81593d6e)
Location: drivers/acpi/ec.c:1522
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81591ff0-ffffffff8159204a: acpi_ec_setup.part.19 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828f18ab)
Location: drivers/acpi/ec.c:1536
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815c2ee0-ffffffff815c2f3a: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828faa1a)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815e4210-ffffffff815e426a: acpi_ec_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_ec_setup(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816912c5)
Location: drivers/acpi/ec.c:1558
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81691988-ffffffff816919e9: acpi_ec_setup.part.0 (STB_LOCAL)
ffffffff81691a5f-ffffffff81691a8c: acpi_ec_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_ec_setup(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816af005)
Location: drivers/acpi/ec.c:1545
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81c015c9-ffffffff81c0162a: acpi_ec_setup.part.0 (STB_LOCAL)
ffffffff81c016a0-ffffffff81c016cd: acpi_ec_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_ec_setup(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8169160e)
Location: drivers/acpi/ec.c:1546
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81bf2e62-ffffffff81bf2ec3: acpi_ec_setup.part.0 (STB_LOCAL)
ffffffff81bf2f39-ffffffff81bf2f66: acpi_ec_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_ec_setup(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81707090)
Location: drivers/acpi/ec.c:1563
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81cef887-ffffffff81cef8e8: acpi_ec_setup.part.0 (STB_LOCAL)
ffffffff81cefad6-ffffffff81cefb03: acpi_ec_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_ec_setup(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff818355b0)
Location: drivers/acpi/ec.c:1569
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81eb73d1-ffffffff81eb743e: acpi_ec_setup.part.0 (STB_LOCAL)
ffffffff81eb7648-ffffffff81eb7679: acpi_ec_setup (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff83ee2982)
Location: drivers/acpi/ec.c:1575
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff819669b0-ffffffff81966a32: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff837083c2)
Location: drivers/acpi/ec.c:1594
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff819acf40-ffffffff819acfc2: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8393b792)
Location: drivers/acpi/ec.c:1594
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff819f7360-ffffffff819f73e2: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffff80001147d81c)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffff800010770480-ffff8000107704f0: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828e36e6)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815d6100-ffffffff815d615a: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828db755)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815bfcc0-ffffffff815bfd1a: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828f6616)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815d84f0-ffffffff815d854a: acpi_ec_setup.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff828fba6e)
Location: drivers/acpi/ec.c:1510
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815f23b0-ffffffff815f240a: acpi_ec_setup.part.0 (STB_LOCAL)
```
</details>
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
</ul>
