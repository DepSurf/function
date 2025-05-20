# Function: <code>acpi_device_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147fff9)
Location: drivers/acpi/scan.c:602
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8147fff9-ffffffff814802be: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce973)
Location: drivers/acpi/scan.c:622
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814ce973-ffffffff814cec34: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f08dd)
Location: drivers/acpi/scan.c:623
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814f08dd-ffffffff814f0b9e: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fdec0)
Location: drivers/acpi/scan.c:621
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814fdec0-ffffffff814fe215: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153fcd0)
Location: drivers/acpi/scan.c:622
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8153fcd0-ffffffff81540025: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:623
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81577c39-ffffffff81577c77: acpi_device_add.cold.17 (STB_LOCAL)
ffffffff81575c60-ffffffff81575f88: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:623
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8158f879-ffffffff8158f8b7: acpi_device_add.cold.17 (STB_LOCAL)
ffffffff8158d880-ffffffff8158dba8: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815c0506-ffffffff815c05da: acpi_device_add.cold (STB_LOCAL)
ffffffff815be670-ffffffff815be913: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815e17c6-ffffffff815e189a: acpi_device_add.cold (STB_LOCAL)
ffffffff815df930-ffffffff815dfbd3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:623
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8168c545-ffffffff8168c61a: acpi_device_add.cold (STB_LOCAL)
ffffffff8168afa0-ffffffff8168b240: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:652
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81c01116-ffffffff81c011bd: acpi_device_add.cold (STB_LOCAL)
ffffffff816a8ce0-ffffffff816a9053: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:647
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81bf2a9f-ffffffff81bf2b46: acpi_device_add.cold (STB_LOCAL)
ffffffff8168b490-ffffffff8168b810: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *adev, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81700f20)
Location: drivers/acpi/scan.c:750
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81700f20-ffffffff81700f84: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *adev, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182eb40)
Location: drivers/acpi/scan.c:768
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8182eb40-ffffffff8182ebac: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81961730)
Location: drivers/acpi/scan.c:675
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81961730-ffffffff81961ac3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a7b40)
Location: drivers/acpi/scan.c:674
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff819a7b40-ffffffff819a7ed3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_device_add(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f0530)
Location: drivers/acpi/scan.c:674
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff819f0530-ffffffff819f08f2: acpi_device_add (STB_GLOBAL)
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
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076c090)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffff80001076c090-ffff80001076c3dc: acpi_device_add (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d3a96-ffffffff815d3b6a: acpi_device_add.cold (STB_LOCAL)
ffffffff815d1d40-ffffffff815d1fe3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815bd656-ffffffff815bd72a: acpi_device_add.cold (STB_LOCAL)
ffffffff815bb900-ffffffff815bbba3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d5aa6-ffffffff815d5b7a: acpi_device_add.cold (STB_LOCAL)
ffffffff815d3c10-ffffffff815d3eb3: acpi_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_device_add(struct acpi_device *device, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:624
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815ef966-ffffffff815efa3a: acpi_device_add.cold (STB_LOCAL)
ffffffff815edad0-ffffffff815edd73: acpi_device_add (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device *adev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_device *device</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device *device</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_device *adev</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*release)(struct device *)</code>
</li>
</ul>
</details>
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
