# Function: <code>acpi_remove_gpe_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81492c68)
Location: drivers/acpi/acpica/evxface.c:940
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff81492c68-ffffffff81492d6d: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff814e1a65)
Location: drivers/acpi/acpica/evxface.c:939
Inline: True
```
**Symbols:**

```
ffffffff814e1a65-ffffffff814e1b68: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815043a4)
Location: drivers/acpi/acpica/evxface.c:939
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff815043a4-ffffffff815044a7: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81514942)
Location: drivers/acpi/acpica/evxface.c:939
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff81514942-ffffffff81514a45: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8155e5d9)
Location: drivers/acpi/acpica/evxface.c:939
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff8155e5d9-ffffffff8155e77c: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8159516d)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff8159516d-ffffffff81595361: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815ad87b)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff815ad87b-ffffffff815ada6f: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815df092)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815df092-ffffffff815df293: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816003d5)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff816003d5-ffffffff816005d6: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ac5ad)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff816ac5ad-ffffffff816ac7ae: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816c9eec)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff816c9eec-ffffffff816ca0ed: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816abecd)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff816abecd-ffffffff816ac0ce: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81722bea)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff81722bea-ffffffff81722deb: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81853084)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff81853084-ffffffff81853287: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8198d5c0)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff8198d5c0-ffffffff8198d805: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff819d4050)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff819d4050-ffffffff819d4295: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81a1ec80)
Location: drivers/acpi/acpica/evxface.c:905
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
```
**Symbols:**

```
ffffffff81a1ec80-ffffffff81a1eec5: acpi_remove_gpe_handler (STB_GLOBAL)
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
Location: include/acpi/acpixf.h:623
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815e8661)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815e8661-ffffffff815e87ca: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815d3c8f)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815d3c8f-ffffffff815d3df8: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815f46b5)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815f46b5-ffffffff815f48b6: acpi_remove_gpe_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_gpe_handler(acpi_handle gpe_device, u32 gpe_number, acpi_gpe_handler address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8160e565)
Location: drivers/acpi/acpica/evxface.c:905
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff8160e565-ffffffff8160e766: acpi_remove_gpe_handler (STB_GLOBAL)
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
