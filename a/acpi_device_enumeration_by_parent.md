# Function: <code>acpi_device_enumeration_by_parent</code>

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
In drivers/acpi/scan.c (ffffffff8154078c)
Location: drivers/acpi/scan.c:1538
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff81576704)
Location: drivers/acpi/scan.c:1539
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff8158e2db)
Location: drivers/acpi/scan.c:1534
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815bef58)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815e0218)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_device_enumeration_by_parent(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168a620)
Location: drivers/acpi/scan.c:1541
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8168a620-ffffffff8168a71a: acpi_device_enumeration_by_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_device_enumeration_by_parent(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8290)
Location: drivers/acpi/scan.c:1607
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff816a8290-ffffffff816a838a: acpi_device_enumeration_by_parent (STB_LOCAL)
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
In drivers/acpi/scan.c (ffffffff8168c0bd)
Location: drivers/acpi/scan.c:1610
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff8170187d)
Location: drivers/acpi/scan.c:1689
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff8182f51c)
Location: drivers/acpi/scan.c:1719
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff81962551)
Location: drivers/acpi/scan.c:1698
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff819a8951)
Location: drivers/acpi/scan.c:1700
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff819f1361)
Location: drivers/acpi/scan.c:1711
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffff80001076cb44)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815d2626)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815bc1e6)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815d44f8)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815ee3b8)
Location: drivers/acpi/scan.c:1532
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
