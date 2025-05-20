# Function: <code>acpi_thermal_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_thermal_check(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff814b0594)
Location: drivers/acpi/thermal.c:516
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff814b0594-ffffffff814b05b4: acpi_thermal_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_thermal_check(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff814ffec7)
Location: drivers/acpi/thermal.c:516
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff814ffec7-ffffffff814ffee7: acpi_thermal_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_thermal_check(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81522f1e)
Location: drivers/acpi/thermal.c:516
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff81522f1e-ffffffff81522f40: acpi_thermal_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff815350e5)
Location: drivers/acpi/thermal.c:516
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff81534f50-ffffffff81534f69: acpi_thermal_check.part.6 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff81596a85)
Location: drivers/acpi/thermal.c:516
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff81596840-ffffffff81596859: acpi_thermal_check.part.6 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff815cde35)
Location: drivers/acpi/thermal.c:516
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff815cdbd0-ffffffff815cdbe9: acpi_thermal_check.part.7 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff815e7355)
Location: drivers/acpi/thermal.c:516
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff815e71b0-ffffffff815e71c9: acpi_thermal_check.part.7 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff81618fe5)
Location: drivers/acpi/thermal.c:502
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff81618e40-ffffffff81618e59: acpi_thermal_check.part.0 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff8163a605)
Location: drivers/acpi/thermal.c:497
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff8163a460-ffffffff8163a479: acpi_thermal_check.part.0 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff816e7575)
Location: drivers/acpi/thermal.c:499
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
  - drivers/acpi/thermal.c:thermal_set_mode
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/acpi/thermal.c (ffff8000107a5de8)
Location: drivers/acpi/thermal.c:497
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffff8000107a5c78-ffff8000107a5ca8: acpi_thermal_check.part.0 (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8162e8e5)
Location: drivers/acpi/thermal.c:497
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff8162e740-ffffffff8162e759: acpi_thermal_check.part.0 (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff81648785)
Location: drivers/acpi/thermal.c:497
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
```
**Symbols:**

```
ffffffff816485e0-ffffffff816485f9: acpi_thermal_check.part.0 (STB_LOCAL)
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
