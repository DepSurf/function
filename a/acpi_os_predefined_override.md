# Function: <code>acpi_os_predefined_override</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, char **new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479e4a)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81479e4a-ffffffff81479ef8: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c843d)
Location: drivers/acpi/osl.c:514
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff814c843d-ffffffff814c84ee: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea381)
Location: drivers/acpi/osl.c:509
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff814ea381-ffffffff814ea432: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6140)
Location: drivers/acpi/osl.c:508
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff814f6140-ffffffff814f61d8: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815368a0)
Location: drivers/acpi/osl.c:508
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815368a0-ffffffff81536938: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:513
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff8156d796-ffffffff8156d7ca: acpi_os_predefined_override.cold.18 (STB_LOCAL)
ffffffff8156c4e0-ffffffff8156c552: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:513
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81585356-ffffffff8158538a: acpi_os_predefined_override.cold.19 (STB_LOCAL)
ffffffff81584110-ffffffff81584182: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:499
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815b5fb8-ffffffff815b5ff4: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815b4d20-ffffffff815b4d8f: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815d71e8-ffffffff815d7224: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815d5f50-ffffffff815d5fbf: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81680fb0-ffffffff81680fec: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff8167fc50-ffffffff8167fcbf: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:523
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81c00918-ffffffff81c00954: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff8169e700-ffffffff8169e76f: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:526
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81bf240d-ffffffff81bf2449: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff816813b0-ffffffff8168141f: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:526
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81ceec9b-ffffffff81ceeced: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff816f6490-ffffffff816f6503: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:525
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff81eb640e-ffffffff81eb6476: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff81823250-ffffffff818232ff: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:525
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff82091707-ffffffff8209171b: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff819543b0-ffffffff819544a6: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:525
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff8211207a-ffffffff8211208e: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff8199a7c0-ffffffff8199a8b6: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:525
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff821efd7e-ffffffff821efd92: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff819e2c40-ffffffff819e2d36: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763790)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffff800010763790-ffff80001076381c: acpi_os_predefined_override (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815ca832-ffffffff815ca86e: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815c9cb0-ffffffff815c9d1f: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815b38b2-ffffffff815b38d1: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815b2d40-ffffffff815b2d91: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815cb4c8-ffffffff815cb504: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815ca230-ffffffff815ca29f: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_predefined_override(const struct acpi_predefined_names *init_val, acpi_string *new_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:519
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815e5368-ffffffff815e53a4: acpi_os_predefined_override.cold (STB_LOCAL)
ffffffff815e4090-ffffffff815e40ff: acpi_os_predefined_override (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char **new_val</code> ➡️ <code>acpi_string *new_val</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
