# Function: <code>acpi_processor_get_info</code>

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
In drivers/acpi/acpi_processor.c (ffffffff814821dc)
Location: drivers/acpi/acpi_processor.c:231
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
In drivers/acpi/acpi_processor.c (ffffffff814d0ce5)
Location: drivers/acpi/acpi_processor.c:231
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
In drivers/acpi/acpi_processor.c (ffffffff814f2d9c)
Location: drivers/acpi/acpi_processor.c:236
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff81500800)
Location: drivers/acpi/acpi_processor.c:231
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81500800-ffffffff81500c76: acpi_processor_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff81542aa0)
Location: drivers/acpi/acpi_processor.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81542aa0-ffffffff81543266: acpi_processor_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815789f0-ffffffff815791a9: acpi_processor_get_info (STB_LOCAL)
ffffffff815794dc-ffffffff815794fe: acpi_processor_get_info.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81590660-ffffffff81590e22: acpi_processor_get_info (STB_LOCAL)
ffffffff8159115c-ffffffff8159117e: acpi_processor_get_info.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815c14a0-ffffffff815c1bf2: acpi_processor_get_info (STB_LOCAL)
ffffffff815c1efa-ffffffff815c1f99: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815e2740-ffffffff815e2eb5: acpi_processor_get_info (STB_LOCAL)
ffffffff815e31ba-ffffffff815e327f: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff8168dea0-ffffffff8168e30a: acpi_processor_get_info (STB_LOCAL)
ffffffff8168e616-ffffffff8168e6db: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff816abc80-ffffffff816ac0ed: acpi_processor_get_info (STB_LOCAL)
ffffffff81c0142c-ffffffff81c014f1: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:217
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff8168e3d0-ffffffff8168e796: acpi_processor_get_info (STB_LOCAL)
ffffffff81bf2cc1-ffffffff81bf2d86: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:217
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81703c30-ffffffff81704048: acpi_processor_get_info (STB_LOCAL)
ffffffff81cef6c1-ffffffff81cef796: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:217
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81831cc0-ffffffff818320f2: acpi_processor_get_info (STB_LOCAL)
ffffffff81eb724c-ffffffff81eb7309: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:217
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81965440-ffffffff819658f7: acpi_processor_get_info (STB_LOCAL)
ffffffff820919d2-ffffffff820919e6: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:246
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff819ab980-ffffffff819abe5e: acpi_processor_get_info (STB_LOCAL)
ffffffff821122f2-ffffffff82112306: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:233
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff819f5d20-ffffffff819f61fe: acpi_processor_get_info (STB_LOCAL)
ffffffff821f005a-ffffffff821f006e: acpi_processor_get_info.cold (STB_LOCAL)
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
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffff80001076f1a8)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffff80001076f1a8-ffff80001076f60c: acpi_processor_get_info (STB_LOCAL)
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
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815d4a00-ffffffff815d4df1: acpi_processor_get_info (STB_LOCAL)
ffffffff815d50fa-ffffffff815d51bf: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815be5c0-ffffffff815be9b1: acpi_processor_get_info (STB_LOCAL)
ffffffff815becba-ffffffff815bed7f: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815d6a20-ffffffff815d7195: acpi_processor_get_info (STB_LOCAL)
ffffffff815d749a-ffffffff815d755f: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_info(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:229
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff815f08e0-ffffffff815f1055: acpi_processor_get_info (STB_LOCAL)
ffffffff815f135a-ffffffff815f141f: acpi_processor_get_info.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
