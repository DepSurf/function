# Function: <code>acpi_hw_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8149ac0c)
Location: drivers/acpi/acpica/hwregs.c:212
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8149ac0c-ffffffff8149ac81: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff814e9c66)
Location: drivers/acpi/acpica/hwregs.c:306
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
```
**Symbols:**

```
ffffffff814e9c66-ffffffff814e9cdb: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8150c4ee)
Location: drivers/acpi/acpica/hwregs.c:306
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
```
**Symbols:**

```
ffffffff8150c4ee-ffffffff8150c563: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8151cb2f)
Location: drivers/acpi/acpica/hwregs.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
```
**Symbols:**

```
ffffffff8151cb2f-ffffffff8151cc39: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8156d1e4)
Location: drivers/acpi/acpica/hwregs.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff8156d1e4-ffffffff8156d35f: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815a3e2c)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff815a3e2c-ffffffff815a3fa7: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815bc7c4)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff815bc7c4-ffffffff815bc93f: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815ee3af)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff815ee3af-ffffffff815ee52d: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160f83d)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff8160f83d-ffffffff8160f9bb: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bbc2a)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff816bbc2a-ffffffff816bbda9: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816d9738)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff816d9738-ffffffff816d98b7: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb6cb)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff816bb6cb-ffffffff816bb84d: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff817327cc)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff817327cc-ffffffff81732999: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81863616)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff81863616-ffffffff818637fc: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff8209218c-ffffffff820921e5: acpi_hw_write.cold (STB_LOCAL)
ffffffff819a1050-ffffffff819a124d: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff82112a80-ffffffff82112ad9: acpi_hw_write.cold (STB_LOCAL)
ffffffff819e7d30-ffffffff819e7f2d: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (0)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/acpica/hwxface.c:acpi_reset
```
**Symbols:**

```
ffffffff821f07d4-ffffffff821f082d: acpi_hw_write.cold (STB_LOCAL)
ffffffff81a32a80-ffffffff81a32c7d: acpi_hw_write (STB_GLOBAL)
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffff80001078afe8)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffff80001078afe8-ffff80001078b114: acpi_hw_write (STB_GLOBAL)
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815f0da9)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff815f0da9-ffffffff815f0ec9: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815dc37b)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff815dc37b-ffffffff815dc49b: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81603b1d)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff81603b1d-ffffffff81603c9b: acpi_hw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8161d9cd)
Location: drivers/acpi/acpica/hwregs.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control
  - drivers/acpi/acpica/hwxface.c:acpi_write
```
**Symbols:**

```
ffffffff8161d9cd-ffffffff8161db4b: acpi_hw_write (STB_GLOBAL)
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
<code>u32 value</code> ➡️ <code>u64 value</code>
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
