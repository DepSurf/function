# Function: <code>acpi_set_gpe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81493569)
Location: drivers/acpi/acpica/evxfgpe.c:214
Inline: False
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81493569-ffffffff814935e1: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e2361)
Location: drivers/acpi/acpica/evxfgpe.c:214
Inline: False
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814e2361-ffffffff814e23d9: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81504ca0)
Location: drivers/acpi/acpica/evxfgpe.c:214
Inline: False
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81504ca0-ffffffff81504d2e: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81515214)
Location: drivers/acpi/acpica/evxfgpe.c:214
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff81515214-ffffffff815152a2: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8155f784)
Location: drivers/acpi/acpica/evxfgpe.c:214
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff8155f784-ffffffff8155f856: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8159657d)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff8159657d-ffffffff81596648: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815aec81)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff815aec81-ffffffff815aed4c: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e04db)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff815e04db-ffffffff815e05a9: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160181e)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff8160181e-ffffffff816018ec: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ada63)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff816ada63-ffffffff816adb31: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cb3a2)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff816cb3a2-ffffffff816cb470: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ad36e)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff816ad36e-ffffffff816ad43c: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8172412d)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff8172412d-ffffffff817241fb: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818546e0)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff818546e0-ffffffff818547b9: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198f020)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_mask_events
```
**Symbols:**

```
ffffffff8198f020-ffffffff8198f0fc: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d5ac0)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_mask_events
```
**Symbols:**

```
ffffffff819d5ac0-ffffffff819d5b9c: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20750)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_mask_events
```
**Symbols:**

```
ffffffff81a20750-ffffffff81a2082c: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: include/acpi/acpixf.h:717
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
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e90a7)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff815e90a7-ffffffff815e9132: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d46cf)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff815d46cf-ffffffff815d475a: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f5afe)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff815f5afe-ffffffff815f5bcc: acpi_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_set_gpe(acpi_handle gpe_device, u32 gpe_number, u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160f9ae)
Location: drivers/acpi/acpica/evxfgpe.c:199
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
```
**Symbols:**

```
ffffffff8160f9ae-ffffffff8160fa7c: acpi_set_gpe (STB_GLOBAL)
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
