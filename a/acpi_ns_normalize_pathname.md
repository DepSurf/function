# Function: <code>acpi_ns_normalize_pathname</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815a9472)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff815c2312)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff815f3ced)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff8161518c)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816c15cd)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff816c15cd-ffffffff816c1681: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816df135)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff816df135-ffffffff816df1e9: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816c1021)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff816c1021-ffffffff816c10d4: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff8173830e)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff8173830e-ffffffff817383c1: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81869698)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff81869698-ffffffff8186974c: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff819a8540)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff819a8540-ffffffff819a863a: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff819ef230)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff819ef230-ffffffff819ef35f: acpi_ns_normalize_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char *original_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81a3a020)
Location: drivers/acpi/acpica/nsnames.c:410
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
**Symbols:**

```
ffffffff81a3a020-ffffffff81a3a14f: acpi_ns_normalize_pathname (STB_GLOBAL)
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
In drivers/acpi/acpica/nsnames.c (ffff80001078dcc4)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff815f3bec)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff815df170)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff8160946c)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
In drivers/acpi/acpica/nsnames.c (ffffffff8162331c)
Location: drivers/acpi/acpica/nsnames.c:414
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
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
