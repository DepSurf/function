# Function: <code>acpi_hw_get_access_bit_width</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff814e9a9a)
Location: drivers/acpi/acpica/hwregs.c:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff814e994b-ffffffff814e997f: acpi_hw_get_access_bit_width.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8150c322)
Location: drivers/acpi/acpica/hwregs.c:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff8150c1d3-ffffffff8150c207: acpi_hw_get_access_bit_width.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8151c7f8)
Location: drivers/acpi/acpica/hwregs.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff8151c7f8-ffffffff8151c8af: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8156ce42)
Location: drivers/acpi/acpica/hwregs.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff8156ce42-ffffffff8156cef9: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815a3a8a)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff815a3a8a-ffffffff815a3b41: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815bc422)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff815bc422-ffffffff815bc4d9: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815ee006)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff815ee006-ffffffff815ee0bd: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160f494)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff8160f494-ffffffff8160f54b: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb871)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff816bb871-ffffffff816bb92e: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816d937f)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff816d937f-ffffffff816d943c: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb30c)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff816bb30c-ffffffff816bb3cb: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81732373)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff81732373-ffffffff81732489: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81863195)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff81863195-ffffffff81863284: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff819a0b90-ffffffff819a0cb5: acpi_hw_get_access_bit_width (STB_LOCAL)
ffffffff820920f7-ffffffff8209211d: acpi_hw_get_access_bit_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff819e7870-ffffffff819e7995: acpi_hw_get_access_bit_width (STB_LOCAL)
ffffffff821129eb-ffffffff82112a11: acpi_hw_get_access_bit_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff81a325c0-ffffffff81a326e5: acpi_hw_get_access_bit_width (STB_LOCAL)
ffffffff821f073f-ffffffff821f0765: acpi_hw_get_access_bit_width.cold (STB_LOCAL)
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffff80001078ac98)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffff80001078ac98-ffff80001078ada0: acpi_hw_get_access_bit_width (STB_LOCAL)
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815f0a5e)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff815f0a5e-ffffffff815f0b15: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815dc030)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff815dc030-ffffffff815dc0e7: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81603774)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff81603774-ffffffff8160382b: acpi_hw_get_access_bit_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address *reg, u8 max_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8161d624)
Location: drivers/acpi/acpica/hwregs.c:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
```
**Symbols:**

```
ffffffff8161d624-ffffffff8161d6db: acpi_hw_get_access_bit_width (STB_LOCAL)
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
