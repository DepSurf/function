# Function: <code>pcc_data_alloc</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81599990)
Location: drivers/acpi/cppc_acpi.c:622
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81599990-ffffffff815999ee: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d11f0)
Location: drivers/acpi/cppc_acpi.c:621
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815d11f0-ffffffff815d124e: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815ea820)
Location: drivers/acpi/cppc_acpi.c:621
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815ea820-ffffffff815ea87e: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161c5a0)
Location: drivers/acpi/cppc_acpi.c:617
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8161c5a0-ffffffff8161c5fe: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163e040)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8163e040-ffffffff8163e09e: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816eb72f)
Location: drivers/acpi/cppc_acpi.c:600
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81708d7f)
Location: drivers/acpi/cppc_acpi.c:580
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816ea399)
Location: drivers/acpi/cppc_acpi.c:572
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81763cfb)
Location: drivers/acpi/cppc_acpi.c:572
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81897c0b)
Location: drivers/acpi/cppc_acpi.c:603
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff819dfef0)
Location: drivers/acpi/cppc_acpi.c:606
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a27c49)
Location: drivers/acpi/cppc_acpi.c:607
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a72de8)
Location: drivers/acpi/cppc_acpi.c:610
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a8ff8)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffff8000107a8ff8-ffff8000107a9074: pcc_data_alloc (STB_GLOBAL)
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
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81609a70)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81609a70-ffffffff81609ace: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815fb6b0)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815fb6b0-ffffffff815fb70e: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81631e80)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81631e80-ffffffff81631ede: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pcc_data_alloc(int pcc_ss_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164c1b0)
Location: drivers/acpi/cppc_acpi.c:619
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8164c1b0-ffffffff8164c20e: pcc_data_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
