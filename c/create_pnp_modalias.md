# Function: <code>create_pnp_modalias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int create_pnp_modalias(struct acpi_device *acpi_dev, char *modalias, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8147bcf1)
Location: drivers/acpi/device_sysfs.c:142
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff8147bcf1-ffffffff8147bde0: create_pnp_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int create_pnp_modalias(struct acpi_device *acpi_dev, char *modalias, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ca3b6)
Location: drivers/acpi/device_sysfs.c:142
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff814ca3b6-ffffffff814ca4b7: create_pnp_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int create_pnp_modalias(struct acpi_device *acpi_dev, char *modalias, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ec2d2)
Location: drivers/acpi/device_sysfs.c:142
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff814ec2d2-ffffffff814ec3d3: create_pnp_modalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int create_pnp_modalias(struct acpi_device *acpi_dev, char *modalias, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814f8b00)
Location: drivers/acpi/device_sysfs.c:142
Inline: False
```
**Symbols:**

```
ffffffff814f8b00-ffffffff814f8c3f: create_pnp_modalias (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff8153a970)
Location: drivers/acpi/device_sysfs.c:142
Inline: True
```
**Symbols:**

```
ffffffff8153a970-ffffffff8153aaaf: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff81570800)
Location: drivers/acpi/device_sysfs.c:142
Inline: True
```
**Symbols:**

```
ffffffff81570800-ffffffff81570928: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815883c0)
Location: drivers/acpi/device_sysfs.c:142
Inline: True
```
**Symbols:**

```
ffffffff815883c0-ffffffff815884e8: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815b9070)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815b9070-ffffffff815b91a3: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815da2b0)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815da2b0-ffffffff815da3e3: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff81684610)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff81684610-ffffffff81684741: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff816a23e0)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff816a23e0-ffffffff816a24f2: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff816850d0)
Location: drivers/acpi/device_sysfs.c:135
Inline: True
```
**Symbols:**

```
ffffffff816850d0-ffffffff816851d4: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff816fa390)
Location: drivers/acpi/device_sysfs.c:135
Inline: True
```
**Symbols:**

```
ffffffff816fa390-ffffffff816fa494: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff8182802f)
Location: drivers/acpi/device_sysfs.c:136
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff81827780-ffffffff8182788a: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff8195a05f)
Location: drivers/acpi/device_sysfs.c:136
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff81959740-ffffffff8195984a: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff819a04bf)
Location: drivers/acpi/device_sysfs.c:136
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff8199fba0-ffffffff8199fcaa: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff819e8b2f)
Location: drivers/acpi/device_sysfs.c:136
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
```
**Symbols:**

```
ffffffff819e8220-ffffffff819e8315: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffff800010766730)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffff800010766730-ffff800010766898: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815cca80)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815cca80-ffffffff815ccbb3: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815b6600)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815b6600-ffffffff815b6733: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815ce590)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815ce590-ffffffff815ce6c3: create_pnp_modalias.part.0 (STB_LOCAL)
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
In drivers/acpi/device_sysfs.c (ffffffff815e8450)
Location: drivers/acpi/device_sysfs.c:134
Inline: True
```
**Symbols:**

```
ffffffff815e8450-ffffffff815e8583: create_pnp_modalias.part.0 (STB_LOCAL)
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
</ul>
