# Function: <code>acpi_data_add_props</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d5e0)
Location: drivers/acpi/property.c:320
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff8159d5e0-ffffffff8159d63f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cebc0)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815cebc0-ffffffff815cec1f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815efe40)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815efe40-ffffffff815efe9f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c1f8)
Location: drivers/acpi/property.c:324
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff8169c630-ffffffff8169c68f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b902e)
Location: drivers/acpi/property.c:327
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff816b94c0-ffffffff816b951f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169afe8)
Location: drivers/acpi/property.c:327
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff8169b490-ffffffff8169b4ef: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710e78)
Location: drivers/acpi/property.c:327
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff81711330-ffffffff8171138f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183fbe4)
Location: drivers/acpi/property.c:327
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff81840310-ffffffff8184037f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976164)
Location: drivers/acpi/property.c:335
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff81976ca0-ffffffff81976d0f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bcad4)
Location: drivers/acpi/property.c:335
Inline: True
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff819bd5a0-ffffffff819bd60f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07790)
Location: drivers/acpi/property.c:339
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff81a07790-ffffffff81a0782e: acpi_data_add_props (STB_GLOBAL)
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
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077ad80)
Location: drivers/acpi/property.c:324
Inline: False
```
**Symbols:**

```
ffff80001077ad80-ffff80001077adec: acpi_data_add_props (STB_GLOBAL)
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
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815dead0)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815dead0-ffffffff815deb2f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ca110)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815ca110-ffffffff815ca16f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e4120)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815e4120-ffffffff815e417f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_device_properties *acpi_data_add_props(struct acpi_device_data *data, const guid_t *guid, const union acpi_object *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fdfe0)
Location: drivers/acpi/property.c:324
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
**Symbols:**

```
ffffffff815fdfe0-ffffffff815fe03f: acpi_data_add_props (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union acpi_object *properties</code> ➡️ <code>union acpi_object *properties</code>
</li>
</ul>
</details>
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
