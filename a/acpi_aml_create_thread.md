# Function: <code>acpi_aml_create_thread</code>

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
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159b070)
Location: drivers/acpi/acpi_dbg.c:428
Inline: False
```
**Symbols:**

```
ffffffff8159b070-ffffffff8159b116: acpi_aml_create_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:428
Inline: False
```
**Symbols:**

```
ffffffff815d2d10-ffffffff815d2da7: acpi_aml_create_thread (STB_LOCAL)
ffffffff815d3d6f-ffffffff815d3d82: acpi_aml_create_thread.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:428
Inline: False
```
**Symbols:**

```
ffffffff815ec4c0-ffffffff815ec557: acpi_aml_create_thread (STB_LOCAL)
ffffffff815ed51f-ffffffff815ed532: acpi_aml_create_thread.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:425
Inline: False
```
**Symbols:**

```
ffffffff8161e290-ffffffff8161e327: acpi_aml_create_thread (STB_LOCAL)
ffffffff8161f2c8-ffffffff8161f2dc: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:425
Inline: False
```
**Symbols:**

```
ffffffff8163fd40-ffffffff8163fdd7: acpi_aml_create_thread (STB_LOCAL)
ffffffff81640da8-ffffffff81640dbc: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:425
Inline: False
```
**Symbols:**

```
ffffffff816ecd00-ffffffff816ecd97: acpi_aml_create_thread (STB_LOCAL)
ffffffff816ede4d-ffffffff816ede61: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff8170a2f0-ffffffff8170a387: acpi_aml_create_thread (STB_LOCAL)
ffffffff81c03307-ffffffff81c0331b: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff816eb9c0-ffffffff816eba57: acpi_aml_create_thread (STB_LOCAL)
ffffffff81bf4cf9-ffffffff81bf4d0d: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff81765ae0-ffffffff81765b77: acpi_aml_create_thread (STB_LOCAL)
ffffffff81cf202b-ffffffff81cf203f: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff81899ed0-ffffffff81899f73: acpi_aml_create_thread (STB_LOCAL)
ffffffff81eba09f-ffffffff81eba0b2: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e2390)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff819e2390-ffffffff819e244e: acpi_aml_create_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2a990)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff81a2a990-ffffffff81a2aa4e: acpi_aml_create_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a75b60)
Location: drivers/acpi/acpi_dbg.c:418
Inline: False
```
**Symbols:**

```
ffffffff81a75b60-ffffffff81a75c1e: acpi_aml_create_thread (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:425
Inline: False
```
**Symbols:**

```
ffffffff81633b80-ffffffff81633c17: acpi_aml_create_thread (STB_LOCAL)
ffffffff81634be8-ffffffff81634bfc: acpi_aml_create_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_aml_create_thread(acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:425
Inline: False
```
**Symbols:**

```
ffffffff8164deb0-ffffffff8164df47: acpi_aml_create_thread (STB_LOCAL)
ffffffff8164ef03-ffffffff8164ef17: acpi_aml_create_thread.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
