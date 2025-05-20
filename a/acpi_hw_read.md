# Function: <code>acpi_hw_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u32 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8149ab06)
Location: drivers/acpi/acpica/hwregs.c:155
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8149ab06-ffffffff8149ab8d: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u32 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff814e9a4d)
Location: drivers/acpi/acpica/hwregs.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
```
**Symbols:**

```
ffffffff814e9a4d-ffffffff814e9bde: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u32 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8150c2d5)
Location: drivers/acpi/acpica/hwregs.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
```
**Symbols:**

```
ffffffff8150c2d5-ffffffff8150c466: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u32 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8151c971)
Location: drivers/acpi/acpica/hwregs.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
```
**Symbols:**

```
ffffffff8151c971-ffffffff8151caa7: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8156cfbb)
Location: drivers/acpi/acpica/hwregs.c:231
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8156cfbb-ffffffff8156d160: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815a3c03)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff815a3c03-ffffffff815a3da8: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815bc59b)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff815bc59b-ffffffff815bc740: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815ee181)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff815ee181-ffffffff815ee329: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160f60f)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8160f60f-ffffffff8160f7b7: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb9f2)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff816bb9f2-ffffffff816bbba5: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816d9500)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff816d9500-ffffffff816d96b3: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb48f)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff816bb48f-ffffffff816bb646: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8173254d)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8173254d-ffffffff81732747: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81863368)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff81863368-ffffffff8186357c: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8209211d-ffffffff8209218c: acpi_hw_read.cold (STB_LOCAL)
ffffffff819a0df0-ffffffff819a1036: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff82112a11-ffffffff82112a80: acpi_hw_read.cold (STB_LOCAL)
ffffffff819e7ad0-ffffffff819e7d16: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff821f0765-ffffffff821f07d4: acpi_hw_read.cold (STB_LOCAL)
ffffffff81a32820-ffffffff81a32a66: acpi_hw_read (STB_GLOBAL)
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
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffff80001078ae94)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffff80001078ae94-ffff80001078afe8: acpi_hw_read (STB_GLOBAL)
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
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815f0bd9)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff815f0bd9-ffffffff815f0d23: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815dc1ab)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff815dc1ab-ffffffff815dc2f5: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816038ef)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff816038ef-ffffffff81603a97: acpi_hw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u64 *value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8161d79f)
Location: drivers/acpi/acpica/hwregs.c:195
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwxface.c:acpi_read
```
**Symbols:**

```
ffffffff8161d79f-ffffffff8161d947: acpi_hw_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 *value</code> ➡️ <code>u64 *value</code>
</li>
</ul>
</details>
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
