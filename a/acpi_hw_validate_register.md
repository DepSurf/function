# Function: <code>acpi_hw_validate_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8149aa66)
Location: drivers/acpi/acpica/hwregs.c:83
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff8149aa66-ffffffff8149ab06: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff814e997f)
Location: drivers/acpi/acpica/hwregs.c:124
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff814e997f-ffffffff814e9a4d: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8150c207)
Location: drivers/acpi/acpica/hwregs.c:124
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff8150c207-ffffffff8150c2d5: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8151c8af)
Location: drivers/acpi/acpica/hwregs.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8151c8af-ffffffff8151c971: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8156cef9)
Location: drivers/acpi/acpica/hwregs.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff8156cef9-ffffffff8156cfbb: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815a3b41)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff815a3b41-ffffffff815a3c03: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815bc4d9)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff815bc4d9-ffffffff815bc59b: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815ee0bd)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff815ee0bd-ffffffff815ee181: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160f54b)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff8160f54b-ffffffff8160f60f: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb92e)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff816bb92e-ffffffff816bb9f2: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816d943c)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff816d943c-ffffffff816d9500: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb3cb)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff816bb3cb-ffffffff816bb48f: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81732489)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff81732489-ffffffff8173254d: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81863284)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff81863284-ffffffff81863368: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff819a0cd0)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff819a0cd0-ffffffff819a0dd5: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff819e79b0)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff819e79b0-ffffffff819e7ab5: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81a32700)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff81a32700-ffffffff81a32805: acpi_hw_validate_register (STB_GLOBAL)
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffff80001078ada0)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffff80001078ada0-ffff80001078ae94: acpi_hw_validate_register (STB_GLOBAL)
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815f0b15)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff815f0b15-ffffffff815f0bd9: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815dc0e7)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff815dc0e7-ffffffff815dc1ab: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160382b)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff8160382b-ffffffff816038ef: acpi_hw_validate_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address *reg, u8 max_bit_width, u64 *address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8161d6db)
Location: drivers/acpi/acpica/hwregs.c:122
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
```
**Symbols:**

```
ffffffff8161d6db-ffffffff8161d79f: acpi_hw_validate_register (STB_GLOBAL)
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
