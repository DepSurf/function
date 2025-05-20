# Function: <code>acpi_any_gpe_status_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81601e0d)
Location: drivers/acpi/acpica/evxfgpe.c:810
Inline: True
```
**Symbols:**

```
ffffffff81601e0d-ffffffff81601e5f: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ae36b)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff816ae36b-ffffffff816ae40c: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cbcaa)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff816cbcaa-ffffffff816cbd4b: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816adc76)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff816adc76-ffffffff816add17: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81724a35)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81724a35-ffffffff81724ad6: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81854b6a)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81854b6a-ffffffff81854c16: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198f550)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff8198f550-ffffffff8198f5f9: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d5ff0)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff819d5ff0-ffffffff819d6099: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 acpi_any_gpe_status_set(u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20c80)
Location: drivers/acpi/acpica/evxfgpe.c:811
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81a20c80-ffffffff81a20d29: acpi_any_gpe_status_set (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e9492)
Location: drivers/acpi/acpica/evxfgpe.c:810
Inline: True
```
**Symbols:**

```
ffffffff815e9492-ffffffff815e94c7: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d4aba)
Location: drivers/acpi/acpica/evxfgpe.c:810
Inline: True
```
**Symbols:**

```
ffffffff815d4aba-ffffffff815d4aef: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f60ed)
Location: drivers/acpi/acpica/evxfgpe.c:810
Inline: True
```
**Symbols:**

```
ffffffff815f60ed-ffffffff815f613f: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_any_gpe_status_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160ff9d)
Location: drivers/acpi/acpica/evxfgpe.c:810
Inline: True
```
**Symbols:**

```
ffffffff8160ff9d-ffffffff8160ffef: acpi_any_gpe_status_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 gpe_skip_number</code>
</li>
</ul>
</details>
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
