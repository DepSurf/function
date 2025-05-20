# Function: <code>register_device_clock</code>

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
In drivers/acpi/acpi_lpss.c (ffffffff81487e46)
Location: drivers/acpi/acpi_lpss.c:273
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff814d6cf4)
Location: drivers/acpi/acpi_lpss.c:305
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff814f9358)
Location: drivers/acpi/acpi_lpss.c:316
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81508449)
Location: drivers/acpi/acpi_lpss.c:360
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8154a83c)
Location: drivers/acpi/acpi_lpss.c:360
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81580b34)
Location: drivers/acpi/acpi_lpss.c:367
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8159879f)
Location: drivers/acpi/acpi_lpss.c:391
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c9d30)
Location: drivers/acpi/acpi_lpss.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815c9d30-ffffffff815c9fb2: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815eaf50)
Location: drivers/acpi/acpi_lpss.c:391
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815eaf50-ffffffff815eb1d2: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816962e0)
Location: drivers/acpi/acpi_lpss.c:384
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff816962e0-ffffffff81696565: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b3430)
Location: drivers/acpi/acpi_lpss.c:391
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff816b3430-ffffffff816b36b5: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816956b0)
Location: drivers/acpi/acpi_lpss.c:392
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff816956b0-ffffffff81695938: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170b3e0)
Location: drivers/acpi/acpi_lpss.c:393
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff8170b3e0-ffffffff8170b66b: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81839930)
Location: drivers/acpi/acpi_lpss.c:412
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff81839930-ffffffff81839bda: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196ef40)
Location: drivers/acpi/acpi_lpss.c:404
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff8196ef40-ffffffff8196f1ea: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b54c0)
Location: drivers/acpi/acpi_lpss.c:419
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff819b54c0-ffffffff819b576a: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819ff840)
Location: drivers/acpi/acpi_lpss.c:407
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff819ff840-ffffffff819ffae7: register_device_clock (STB_LOCAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5970)
Location: drivers/acpi/acpi_lpss.c:391
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815c5970-ffffffff815c5bf2: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815df230)
Location: drivers/acpi/acpi_lpss.c:391
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815df230-ffffffff815df4b2: register_device_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device *adev, struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f90f0)
Location: drivers/acpi/acpi_lpss.c:391
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815f90f0-ffffffff815f9372: register_device_clock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
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
