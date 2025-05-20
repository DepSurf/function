# Function: <code>find_guid_info</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *find_guid_info(const guid_t *guid, u8 mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81713570)
Location: drivers/acpi/prmt.c:153
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
**Symbols:**

```
ffffffff81713570-ffffffff817135ee: find_guid_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *find_guid_info(const guid_t *guid, u8 mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81842c30)
Location: drivers/acpi/prmt.c:171
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
**Symbols:**

```
ffffffff81842c30-ffffffff81842ccb: find_guid_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *find_guid_info(const guid_t *guid, u8 mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81979d40)
Location: drivers/acpi/prmt.c:171
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
**Symbols:**

```
ffffffff81979d40-ffffffff81979ddb: find_guid_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *find_guid_info(const guid_t *guid, u8 mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff819c07d0)
Location: drivers/acpi/prmt.c:171
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
**Symbols:**

```
ffffffff819c07d0-ffffffff819c086b: find_guid_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *find_guid_info(const guid_t *guid, u8 mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81a0b250)
Location: drivers/acpi/prmt.c:171
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
**Symbols:**

```
ffffffff81a0b250-ffffffff81a0b2eb: find_guid_info (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
