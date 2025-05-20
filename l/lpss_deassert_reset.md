# Function: <code>lpss_deassert_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81487666)
Location: drivers/acpi/acpi_lpss.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81487666-ffffffff8148768b: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814d62d8)
Location: drivers/acpi/acpi_lpss.c:133
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff814d62d8-ffffffff814d62fd: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814f8938)
Location: drivers/acpi/acpi_lpss.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff814f8938-ffffffff814f895d: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81507d6e)
Location: drivers/acpi/acpi_lpss.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81507710-ffffffff81507737: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8154a1d9)
Location: drivers/acpi/acpi_lpss.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81549b80-ffffffff81549ba7: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815803e3)
Location: drivers/acpi/acpi_lpss.c:141
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff8157fce0-ffffffff8157fd07: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815982f3)
Location: drivers/acpi/acpi_lpss.c:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81597a70-ffffffff81597a97: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c9482)
Location: drivers/acpi/acpi_lpss.c:143
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff815c8c20-ffffffff815c8c47: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea6a2)
Location: drivers/acpi/acpi_lpss.c:144
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff815e9e40-ffffffff815e9e67: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8169706a)
Location: drivers/acpi/acpi_lpss.c:140
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81695850-ffffffff81695877: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b41de)
Location: drivers/acpi/acpi_lpss.c:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff816b2980-ffffffff816b29a7: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8169640e)
Location: drivers/acpi/acpi_lpss.c:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81694c10-ffffffff81694c37: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170c1ae)
Location: drivers/acpi/acpi_lpss.c:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff8170a900-ffffffff8170a927: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8183a7d9)
Location: drivers/acpi/acpi_lpss.c:147
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff81838de0-ffffffff81838e11: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196fe79)
Location: drivers/acpi/acpi_lpss.c:147
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff8196e290-ffffffff8196e2c1: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b6416)
Location: drivers/acpi/acpi_lpss.c:147
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff819b47d0-ffffffff819b4801: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81a00996)
Location: drivers/acpi/acpi_lpss.c:147
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff819fedd0-ffffffff819fee01: lpss_deassert_reset (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5112)
Location: drivers/acpi/acpi_lpss.c:144
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff815c48a0-ffffffff815c48c7: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815de982)
Location: drivers/acpi/acpi_lpss.c:144
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff815de120-ffffffff815de147: lpss_deassert_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lpss_deassert_reset(struct lpss_private_data *pdata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8842)
Location: drivers/acpi/acpi_lpss.c:144
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
**Symbols:**

```
ffffffff815f7fe0-ffffffff815f8007: lpss_deassert_reset (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
