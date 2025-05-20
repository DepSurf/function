# Function: <code>validate_dsm</code>

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
int validate_dsm(acpi_handle handle, const char *uuid, int rev, guid_t *dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81712070)
Location: drivers/acpi/x86/s2idle.c:340
Inline: False
```
**Symbols:**

```
ffffffff81712070-ffffffff81712132: validate_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int validate_dsm(acpi_handle handle, const char *uuid, int rev, guid_t *dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff818413c0)
Location: drivers/acpi/x86/s2idle.c:342
Inline: False
```
**Symbols:**

```
ffffffff818413c0-ffffffff8184148e: validate_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int validate_dsm(acpi_handle handle, const char *uuid, int rev, guid_t *dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81977e60)
Location: drivers/acpi/x86/s2idle.c:343
Inline: False
```
**Symbols:**

```
ffffffff81977e60-ffffffff81977f2e: validate_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int validate_dsm(acpi_handle handle, const char *uuid, int rev, guid_t *dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff819be740)
Location: drivers/acpi/x86/s2idle.c:376
Inline: False
```
**Symbols:**

```
ffffffff819be740-ffffffff819be80e: validate_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int validate_dsm(acpi_handle handle, const char *uuid, int rev, guid_t *dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81a09a70)
Location: drivers/acpi/x86/s2idle.c:414
Inline: False
```
**Symbols:**

```
ffffffff81a09a70-ffffffff81a09b48: validate_dsm (STB_LOCAL)
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
