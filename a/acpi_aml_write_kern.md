# Function: <code>acpi_aml_write_kern</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159b788)
Location: drivers/acpi/acpi_dbg.c:260
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
In drivers/acpi/acpi_dbg.c (ffffffff815d36e7)
Location: drivers/acpi/acpi_dbg.c:260
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
In drivers/acpi/acpi_dbg.c (ffffffff815ece97)
Location: drivers/acpi/acpi_dbg.c:260
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161ec56)
Location: drivers/acpi/acpi_dbg.c:257
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81640706)
Location: drivers/acpi/acpi_dbg.c:257
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ed9b0)
Location: drivers/acpi/acpi_dbg.c:257
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff816ed9b0-ffffffff816eda84: acpi_aml_write_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8170afc0)
Location: drivers/acpi/acpi_dbg.c:250
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8170afc0-ffffffff8170b094: acpi_aml_write_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ec476)
Location: drivers/acpi/acpi_dbg.c:250
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff817665a9)
Location: drivers/acpi/acpi_dbg.c:250
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8189a78c)
Location: drivers/acpi/acpi_dbg.c:250
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e2840)
Location: drivers/acpi/acpi_dbg.c:250
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff819e2840-ffffffff819e2919: acpi_aml_write_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2ae40)
Location: drivers/acpi/acpi_dbg.c:250
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81a2ae40-ffffffff81a2af19: acpi_aml_write_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a76010)
Location: drivers/acpi/acpi_dbg.c:250
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81a76010-ffffffff81a760e9: acpi_aml_write_kern (STB_LOCAL)
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81634546)
Location: drivers/acpi/acpi_dbg.c:257
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164e866)
Location: drivers/acpi/acpi_dbg.c:257
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
