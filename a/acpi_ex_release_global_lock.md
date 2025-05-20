# Function: <code>acpi_ex_release_global_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81499f9a)
Location: drivers/acpi/acpica/exutils.c:233
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
```
**Symbols:**

```
ffffffff81499f9a-ffffffff81499fd5: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff814e8ea3)
Location: drivers/acpi/acpica/exutils.c:233
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff814e8ea3-ffffffff814e8ede: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8150b6f2)
Location: drivers/acpi/acpica/exutils.c:241
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8150b6f2-ffffffff8150b72d: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8151bd23)
Location: drivers/acpi/acpica/exutils.c:241
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8151bd23-ffffffff8151bd5f: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8156bc53)
Location: drivers/acpi/acpica/exutils.c:241
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8156bc53-ffffffff8156bce5: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815a28ab)
Location: drivers/acpi/acpica/exutils.c:207
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff815a28ab-ffffffff815a293d: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815bb56e)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815bb56e-ffffffff815bb600: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815ed14f)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815ed14f-ffffffff815ed1e1: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8160e4e4)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff8160e4e4-ffffffff8160e576: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba842)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816ba842-ffffffff816ba8d4: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816d823a)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816d823a-ffffffff816d82cc: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba1cc)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816ba1cc-ffffffff816ba25e: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8173121c)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff8173121c-ffffffff817312ae: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81861e75)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81861e75-ffffffff81861f15: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8199f2a0)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff8199f2a0-ffffffff8199f35c: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff819e5f70)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff819e5f70-ffffffff819e602c: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81a30cc0)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81a30cc0-ffffffff81a30d7c: acpi_ex_release_global_lock (STB_GLOBAL)
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
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffff80001078a774)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffff80001078a774-ffff80001078a7c8: acpi_ex_release_global_lock (STB_GLOBAL)
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
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815f00c3)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815f00c3-ffffffff815f00ff: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815db69a)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815db69a-ffffffff815db6d6: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816027c4)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816027c4-ffffffff81602856: acpi_ex_release_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ex_release_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8161c674)
Location: drivers/acpi/acpica/exutils.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff8161c674-ffffffff8161c706: acpi_ex_release_global_lock (STB_GLOBAL)
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
