# Function: <code>acpi_aml_busy</code>

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
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159af20)
Location: drivers/acpi/acpi_dbg.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff8159af20-ffffffff8159af51: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815d2bc0)
Location: drivers/acpi/acpi_dbg.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff815d2bc0-ffffffff815d2bf1: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815ec370)
Location: drivers/acpi/acpi_dbg.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff815ec370-ffffffff815ec3a1: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161e140)
Location: drivers/acpi/acpi_dbg.c:142
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff8161e140-ffffffff8161e175: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8163fbf0)
Location: drivers/acpi/acpi_dbg.c:142
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff8163fbf0-ffffffff8163fc25: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ed5b5)
Location: drivers/acpi/acpi_dbg.c:142
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8170abc5)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
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
In drivers/acpi/acpi_dbg.c (ffffffff816ec265)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
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
In drivers/acpi/acpi_dbg.c (ffffffff8176637f)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
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
In drivers/acpi/acpi_dbg.c (ffffffff8189a513)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e2b19)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2b119)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a762e9)
Location: drivers/acpi/acpi_dbg.c:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
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
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81633a30)
Location: drivers/acpi/acpi_dbg.c:142
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff81633a30-ffffffff81633a65: acpi_aml_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_aml_busy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164dd60)
Location: drivers/acpi/acpi_dbg.c:142
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
```
**Symbols:**

```
ffffffff8164dd60-ffffffff8164dd95: acpi_aml_busy (STB_LOCAL)
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
