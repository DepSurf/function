# Function: <code>acpi_ex_acquire_global_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81499f51)
Location: drivers/acpi/acpica/exutils.c:194
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
```
**Symbols:**

```
ffffffff81499f51-ffffffff81499f9a: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff814e8e5a)
Location: drivers/acpi/acpica/exutils.c:194
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff814e8e5a-ffffffff814e8ea3: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8150b6a9)
Location: drivers/acpi/acpica/exutils.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8150b6a9-ffffffff8150b6f2: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8151bcd9)
Location: drivers/acpi/acpica/exutils.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8151bcd9-ffffffff8151bd23: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8156bbb3)
Location: drivers/acpi/acpica/exutils.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8156bbb3-ffffffff8156bc53: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815a280b)
Location: drivers/acpi/acpica/exutils.c:168
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff815a280b-ffffffff815a28ab: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815bb4ce)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff815bb4ce-ffffffff815bb56e: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815ed0af)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff815ed0af-ffffffff815ed14f: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8160e444)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff8160e444-ffffffff8160e4e4: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba7a2)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff816ba7a2-ffffffff816ba842: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816d819a)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff816d819a-ffffffff816d823a: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba12c)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff816ba12c-ffffffff816ba1cc: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8173117c)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff8173117c-ffffffff8173121c: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81861dc7)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff81861dc7-ffffffff81861e75: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8199f1c0)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff8199f1c0-ffffffff8199f28a: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff819e5e90)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff819e5e90-ffffffff819e5f5a: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81a30be0)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff81a30be0-ffffffff81a30caa: acpi_ex_acquire_global_lock (STB_GLOBAL)
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
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffff80001078a718)
Location: drivers/acpi/acpica/exutils.c:167
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
ffff80001078a718-ffff80001078a774: acpi_ex_acquire_global_lock (STB_GLOBAL)
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
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815f0079)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff815f0079-ffffffff815f00c3: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815db650)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff815db650-ffffffff815db69a: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81602724)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff81602724-ffffffff816027c4: acpi_ex_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ex_acquire_global_lock(u32 field_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8161c5d4)
Location: drivers/acpi/acpica/exutils.c:167
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
ffffffff8161c5d4-ffffffff8161c674: acpi_ex_acquire_global_lock (STB_GLOBAL)
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
