# Function: <code>acpi_power_resources_list_add</code>

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
In drivers/acpi/power.c (ffffffff814893df)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff814d81d2)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff814fa8ba)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff81509d0a)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff8154c20a)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff8158271a)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff8159a82f)
Location: drivers/acpi/power.c:97
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff815cbf94)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff815ed214)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_power_resources_list_add(acpi_handle handle, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81698090)
Location: drivers/acpi/power.c:88
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81698090-ffffffff81698185: acpi_power_resources_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_power_resources_list_add(acpi_handle handle, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b51c0)
Location: drivers/acpi/power.c:88
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff816b51c0-ffffffff816b52b5: acpi_power_resources_list_add (STB_LOCAL)
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
In drivers/acpi/power.c (ffffffff81697f68)
Location: drivers/acpi/power.c:89
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff8170dd0a)
Location: drivers/acpi/power.c:92
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff8183c687)
Location: drivers/acpi/power.c:92
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff81972067)
Location: drivers/acpi/power.c:92
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff819b8708)
Location: drivers/acpi/power.c:93
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff81a02d08)
Location: drivers/acpi/power.c:93
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff8000107789d4)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815dc304)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c7944)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e14f4)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
In drivers/acpi/power.c (ffffffff815fb3b4)
Location: drivers/acpi/power.c:90
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_extract_power_resources
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
</ul>
