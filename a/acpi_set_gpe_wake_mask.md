# Function: <code>acpi_set_gpe_wake_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814935e1)
Location: drivers/acpi/acpica/evxfgpe.c:456
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
```
**Symbols:**

```
ffffffff814935e1-ffffffff81493697: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e23d9)
Location: drivers/acpi/acpica/evxfgpe.c:456
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff814e23d9-ffffffff814e248f: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81504d92)
Location: drivers/acpi/acpica/evxfgpe.c:499
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff81504d92-ffffffff81504e48: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81515306)
Location: drivers/acpi/acpica/evxfgpe.c:507
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff81515306-ffffffff815153bc: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8155f8f8)
Location: drivers/acpi/acpica/evxfgpe.c:507
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff8155f8f8-ffffffff8155f9e9: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815966ea)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff815966ea-ffffffff815967db: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815aedee)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff815aedee-ffffffff815aeedf: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e064c)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff815e064c-ffffffff815e073f: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160198f)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff8160198f-ffffffff81601a82: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816adbd4)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff816adbd4-ffffffff816adcc7: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cb513)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff816cb513-ffffffff816cb606: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ad4df)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff816ad4df-ffffffff816ad5d2: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8172429e)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff8172429e-ffffffff81724391: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8185486a)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff8185486a-ffffffff8185496e: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198f1e0)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff8198f1e0-ffffffff8198f2e6: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d5c80)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff819d5c80-ffffffff819d5d82: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20910)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff81a20910-ffffffff81a20a12: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (0)
Location: include/acpi/acpixf.h:738
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/acpi/acpixf.h:738
Inline: True
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
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e9195)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
**Symbols:**

```
ffffffff815e9195-ffffffff815e924d: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d47bd)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff815d47bd-ffffffff815d4875: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f5c6f)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff815f5c6f-ffffffff815f5d62: acpi_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_set_gpe_wake_mask(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160fb1f)
Location: drivers/acpi/acpica/evxfgpe.c:492
Inline: False
Direct callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
```
**Symbols:**

```
ffffffff8160fb1f-ffffffff8160fc12: acpi_set_gpe_wake_mask (STB_GLOBAL)
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
