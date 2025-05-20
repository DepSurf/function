# Function: <code>crb_map_io</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81660106)
Location: drivers/char/tpm/tpm_crb.c:484
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e759)
Location: drivers/char/tpm/tpm_crb.c:494
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816b52f0-ffffffff816b5629: crb_map_io (STB_LOCAL)
ffffffff816b5821-ffffffff816b58d6: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816d7fd0-ffffffff816d8309: crb_map_io (STB_LOCAL)
ffffffff816d8501-ffffffff816d85b6: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8178c500-ffffffff8178c9f2: crb_map_io (STB_LOCAL)
ffffffff8178cbf8-ffffffff8178cd7e: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff817a2a90-ffffffff817a2fa0: crb_map_io (STB_LOCAL)
ffffffff81c0b1bc-ffffffff81c0b330: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81785790-ffffffff81785ca7: crb_map_io (STB_LOCAL)
ffffffff81bfcc3b-ffffffff81bfcdb3: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8180c2d0-ffffffff8180cb36: crb_map_io (STB_LOCAL)
ffffffff81cfd9f1-ffffffff81cfdb71: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8194c980-ffffffff8194d198: crb_map_io (STB_LOCAL)
ffffffff81ec630e-ffffffff81ec647f: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0ab0)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81ab0ab0-ffffffff81ab1429: crb_map_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc9b0)
Location: drivers/char/tpm/tpm_crb.c:548
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81afc9b0-ffffffff81afd346: crb_map_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4ffc0)
Location: drivers/char/tpm/tpm_crb.c:548
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81b4ffc0-ffffffff81b50956: crb_map_io (STB_LOCAL)
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
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffff8000108c35d0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffff8000108c35d0-ffff8000108c39c0: crb_map_io (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8169da20-ffffffff8169dd59: crb_map_io (STB_LOCAL)
ffffffff8169df51-ffffffff8169e006: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8167b410-ffffffff8167b749: crb_map_io (STB_LOCAL)
ffffffff8167b941-ffffffff8167b9f6: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816cbc90-ffffffff816cbfc9: crb_map_io (STB_LOCAL)
ffffffff816cc1c1-ffffffff816cc276: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crb_map_io(struct acpi_device *device, struct crb_priv *priv, struct acpi_table_tpm2 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:490
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816e6160-ffffffff816e6499: crb_map_io (STB_LOCAL)
ffffffff816e6691-ffffffff816e6746: crb_map_io.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
