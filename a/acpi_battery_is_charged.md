# Function: <code>acpi_battery_is_charged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_is_charged(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1ff7)
Location: drivers/acpi/battery.c:174
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff814b1ff7-ffffffff814b2036: acpi_battery_is_charged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_is_charged(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81501911)
Location: drivers/acpi/battery.c:174
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81501911-ffffffff81501950: acpi_battery_is_charged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_is_charged(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81524494)
Location: drivers/acpi/battery.c:174
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81524494-ffffffff815244d3: acpi_battery_is_charged (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff81537661)
Location: drivers/acpi/battery.c:180
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81598db6)
Location: drivers/acpi/battery.c:181
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff815d051d)
Location: drivers/acpi/battery.c:183
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff815e9b1b)
Location: drivers/acpi/battery.c:183
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff8161b8cc)
Location: drivers/acpi/battery.c:170
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff8163d346)
Location: drivers/acpi/battery.c:172
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff816e9f56)
Location: drivers/acpi/battery.c:172
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81707749)
Location: drivers/acpi/battery.c:161
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff816e92f9)
Location: drivers/acpi/battery.c:156
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81762935)
Location: drivers/acpi/battery.c:157
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff818965d0)
Location: drivers/acpi/battery.c:154
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff819de56d)
Location: drivers/acpi/battery.c:154
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81a26147)
Location: drivers/acpi/battery.c:156
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81a70ff7)
Location: drivers/acpi/battery.c:156
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffff8000107a7a08)
Location: drivers/acpi/battery.c:172
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff81631186)
Location: drivers/acpi/battery.c:172
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
In drivers/acpi/battery.c (ffffffff8164b4c6)
Location: drivers/acpi/battery.c:172
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:acpi_battery_get_property
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
</ul>
