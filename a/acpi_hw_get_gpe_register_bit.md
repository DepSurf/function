# Function: <code>acpi_hw_get_gpe_register_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8149a615)
Location: drivers/acpi/acpica/hwgpe.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
```
**Symbols:**

```
ffffffff8149a615-ffffffff8149a632: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff814e9520)
Location: drivers/acpi/acpica/hwgpe.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff814e9520-ffffffff814e953d: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8150bd79)
Location: drivers/acpi/acpica/hwgpe.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff8150bd79-ffffffff8150bd96: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8151c3ae)
Location: drivers/acpi/acpica/hwgpe.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff8151c3ae-ffffffff8151c3cb: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8156c7d3)
Location: drivers/acpi/acpica/hwgpe.c:74
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff8156c7d3-ffffffff8156c7f0: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815a33ea)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff815a33ea-ffffffff815a3407: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815bc0b5)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff815bc0b5-ffffffff815bc0d2: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815edc95)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff815edc95-ffffffff815edcb2: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8160f0b9)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff8160f0b9-ffffffff8160f0d6: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816bb42c)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816bb42c-ffffffff816bb449: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816d8f3a)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816d8f3a-ffffffff816d8f57: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816baed2)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816baed2-ffffffff816baeef: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81731f19)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81731f19-ffffffff81731f56: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81862cc8)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81862cc8-ffffffff81862d11: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819a0b13)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff82092041-ffffffff82092075: acpi_hw_get_gpe_register_bit.cold (STB_LOCAL)
ffffffff819a0490-ffffffff819a04c0: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819e77f3)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff82112916-ffffffff8211294a: acpi_hw_get_gpe_register_bit.cold (STB_LOCAL)
ffffffff819e7160-ffffffff819e7190: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81a32543)
Location: drivers/acpi/acpica/hwgpe.c:110
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff821f066a-ffffffff821f069e: acpi_hw_get_gpe_register_bit.cold (STB_LOCAL)
ffffffff81a31eb0-ffffffff81a31ee0: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815f078f)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff815f078f-ffffffff815f07ac: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815dbd61)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_update_gpe_enable_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff815dbd61-ffffffff815dbd7e: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81603399)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81603399-ffffffff816033b6: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 acpi_hw_get_gpe_register_bit(struct acpi_gpe_event_info *gpe_event_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8161d249)
Location: drivers/acpi/acpica/hwgpe.c:40
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff8161d249-ffffffff8161d266: acpi_hw_get_gpe_register_bit (STB_GLOBAL)
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
