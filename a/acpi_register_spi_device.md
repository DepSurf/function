# Function: <code>acpi_register_spi_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_master *master, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81647810)
Location: drivers/spi/spi.c:1667
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81647810-ffffffff816479d5: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_master *master, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81678900)
Location: drivers/spi/spi.c:1694
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81678900-ffffffff81678ac5: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168d1a0)
Location: drivers/spi/spi.c:1743
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff8168d1a0-ffffffff8168d35c: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f6b90)
Location: drivers/spi/spi.c:1771
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff816f6b90-ffffffff816f6ed2: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81732030)
Location: drivers/spi/spi.c:1785
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81732030-ffffffff81732356: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81754a20)
Location: drivers/spi/spi.c:1851
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81754a20-ffffffff81754d46: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1970
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81790260-ffffffff81790582: acpi_register_spi_device (STB_LOCAL)
ffffffff81792986-ffffffff817929ee: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff817b3e40-ffffffff817b416b: acpi_register_spi_device (STB_LOCAL)
ffffffff817b64e8-ffffffff817b6550: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2154
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff8187b520-ffffffff8187b720: acpi_register_spi_device (STB_LOCAL)
ffffffff8187d401-ffffffff8187d469: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2187
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff8188a1d0-ffffffff8188a3df: acpi_register_spi_device (STB_LOCAL)
ffffffff81c18e56-ffffffff81c18ebe: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2206
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff8186cbb0-ffffffff8186cdbc: acpi_register_spi_device (STB_LOCAL)
ffffffff81c0ac84-ffffffff81c0acec: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2334
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff818fca60-ffffffff818fcc6c: acpi_register_spi_device (STB_LOCAL)
ffffffff81d0fe13-ffffffff81d0fe7b: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2515
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81a4e180-ffffffff81a4e25e: acpi_register_spi_device (STB_LOCAL)
ffffffff81edab39-ffffffff81edab7a: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd86c0)
Location: drivers/spi/spi.c:2692
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81bd86c0-ffffffff81bd87d5: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2f0b0)
Location: drivers/spi/spi.c:2701
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81c2f0b0-ffffffff81c2f1c4: acpi_register_spi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce1cf0)
Location: drivers/spi/spi.c:2855
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81ce1cf0-ffffffff81ce1e3e: acpi_register_spi_device (STB_LOCAL)
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
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c31a8)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffff8000109c31a8-ffff8000109c33b0: acpi_register_spi_device (STB_LOCAL)
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
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff81778920-ffffffff81778c4b: acpi_register_spi_device (STB_LOCAL)
ffffffff8177afc8-ffffffff8177b030: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff817586d0-ffffffff817589fb: acpi_register_spi_device (STB_LOCAL)
ffffffff8175ad78-ffffffff8175ade0: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff817a8cc0-ffffffff817a8feb: acpi_register_spi_device (STB_LOCAL)
ffffffff817ab368-ffffffff817ab3d0: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_register_spi_device(struct spi_controller *ctlr, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1973
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff817c2b50-ffffffff817c2e7b: acpi_register_spi_device (STB_LOCAL)
ffffffff817c52f8-ffffffff817c5360: acpi_register_spi_device.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct spi_controller *ctlr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct spi_master *master</code>
</li>
</ul>
</details>
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
