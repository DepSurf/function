# Function: <code>acpi_ns_copy_device_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8149feef)
Location: drivers/acpi/acpica/nsxfname.c:237
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff8149feef-ffffffff8149ff15: acpi_ns_copy_device_id (STB_LOCAL)
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
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef75e)
Location: drivers/acpi/acpica/nsxfname.c:237
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
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
In drivers/acpi/acpica/nsxfname.c (ffffffff815121b3)
Location: drivers/acpi/acpica/nsxfname.c:216
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81522419)
Location: drivers/acpi/acpica/nsxfname.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff81522419-ffffffff8152243f: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576b9d)
Location: drivers/acpi/acpica/nsxfname.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff81576b9d-ffffffff81576bc3: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815adb1b)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff815adb1b-ffffffff815adb3f: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6b0a)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff815c6b0a-ffffffff815c6b2e: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8425)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff815f8425-ffffffff815f8449: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816198cb)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff816198cb-ffffffff816198ef: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5e22)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff816c5e22-ffffffff816c5e46: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e3e44)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff816e3e44-ffffffff816e3e68: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5d16)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff816c5d16-ffffffff816c5d3a: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d07b)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff8173d07b-ffffffff8173d09f: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186e87d)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff8186e87d-ffffffff8186e8ad: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819ae940)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff819ae940-ffffffff819ae97e: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5810)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff819f5810-ffffffff819f584e: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40660)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff81a40660-ffffffff81a4069e: acpi_ns_copy_device_id (STB_LOCAL)
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
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffff800010791340)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffff800010791340-ffff800010791398: acpi_ns_copy_device_id (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6a2d)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff815f6a2d-ffffffff815f6a51: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e1f75)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff815e1f75-ffffffff815e1f99: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160dbab)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff8160dbab-ffffffff8160dbcf: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *acpi_ns_copy_device_id(struct acpi_pnp_device_id *dest, struct acpi_pnp_device_id *source, char *string_area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627a5b)
Location: drivers/acpi/acpica/nsxfname.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
**Symbols:**

```
ffffffff81627a5b-ffffffff81627a7f: acpi_ns_copy_device_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
