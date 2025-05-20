# Function: <code>acpi_rs_out_integer8</code>

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
In drivers/acpi/acpica/rsdump.c (ffffffff8158dc83)
Location: drivers/acpi/acpica/rsdump.c:534
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff815c4fc4)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff815de593)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff816100b8)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81631561)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_rs_out_integer8(const char *title, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816dddc6)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816dddc6-ffffffff816ddde4: acpi_rs_out_integer8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_rs_out_integer8(const char *title, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816fbe5c)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816fbe5c-ffffffff816fbe7a: acpi_rs_out_integer8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_rs_out_integer8(const char *title, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816ddcf8)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816ddcf8-ffffffff816ddd16: acpi_rs_out_integer8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_rs_out_integer8(const char *title, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff81755de8)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff81755de8-ffffffff81755e06: acpi_rs_out_integer8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_rs_out_integer8(const char *title, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff81888eba)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff81888eba-ffffffff81888ee2: acpi_rs_out_integer8 (STB_LOCAL)
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
In drivers/acpi/acpica/rsdump.c (ffffffff819cf62e)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81a16bbb)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81a61d9b)
Location: drivers/acpi/acpica/rsdump.c:506
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81625841)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff8163f6f1)
Location: drivers/acpi/acpica/rsdump.c:498
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
