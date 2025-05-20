# Function: <code>acpi_ec_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_ec_read(struct acpi_ec *ec, u8 address, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483e87)
Location: drivers/acpi/ec.c:750
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_read
  - drivers/acpi/ec.c:acpi_ec_space_handler
```
**Symbols:**

```
ffffffff81483e87-ffffffff81483f01: acpi_ec_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_ec_read(struct acpi_ec *ec, u8 address, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d28f2)
Location: drivers/acpi/ec.c:757
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff814d28f2-ffffffff814d296c: acpi_ec_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_ec_read(struct acpi_ec *ec, u8 address, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f4dc3)
Location: drivers/acpi/ec.c:871
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff814f4dc3-ffffffff814f4e3d: acpi_ec_read (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8150341e)
Location: drivers/acpi/ec.c:860
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff8154587e)
Location: drivers/acpi/ec.c:862
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff8157be9e)
Location: drivers/acpi/ec.c:862
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff8159355e)
Location: drivers/acpi/ec.c:862
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815c4528)
Location: drivers/acpi/ec.c:876
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815e5768)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff816914d7)
Location: drivers/acpi/ec.c:864
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff816af217)
Location: drivers/acpi/ec.c:851
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff81691827)
Location: drivers/acpi/ec.c:852
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff8170725d)
Location: drivers/acpi/ec.c:854
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff818351f7)
Location: drivers/acpi/ec.c:877
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff81968bd7)
Location: drivers/acpi/ec.c:878
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff819af195)
Location: drivers/acpi/ec.c:863
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff819f9645)
Location: drivers/acpi/ec.c:863
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffff8000107723e8)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815d7658)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815c1218)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815d9a48)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
In drivers/acpi/ec.c (ffffffff815f3908)
Location: drivers/acpi/ec.c:868
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:ec_read
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
