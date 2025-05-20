# Function: <code>check_acpi_tpm2</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff815beb40)
Location: drivers/char/tpm/tpm_tis.c:103
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff815beb40-ffffffff815bebde: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81625400)
Location: drivers/char/tpm/tpm_tis.c:104
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81625400-ffffffff8162549e: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8165f720)
Location: drivers/char/tpm/tpm_tis.c:104
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8165f720-ffffffff8165f7be: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8167dbe0)
Location: drivers/char/tpm/tpm_tis.c:104
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8167dbe0-ffffffff8167dc7e: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816b4920-ffffffff816b49b2: check_acpi_tpm2 (STB_LOCAL)
ffffffff816b4ce7-ffffffff816b4d00: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816d7600-ffffffff816d7692: check_acpi_tpm2 (STB_LOCAL)
ffffffff816d79c7-ffffffff816d79e0: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8178bae0-ffffffff8178bb70: check_acpi_tpm2 (STB_LOCAL)
ffffffff8178be97-ffffffff8178beb0: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:123
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff817a2080-ffffffff817a2110: check_acpi_tpm2 (STB_LOCAL)
ffffffff81c0b0a2-ffffffff81c0b0bb: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:123
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81784d70-ffffffff81784e00: check_acpi_tpm2 (STB_LOCAL)
ffffffff81bfcb1e-ffffffff81bfcb37: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:123
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8180b8a0-ffffffff8180b930: check_acpi_tpm2 (STB_LOCAL)
ffffffff81cfd8bf-ffffffff81cfd8d8: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:123
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8194bde0-ffffffff8194be81: check_acpi_tpm2 (STB_LOCAL)
ffffffff81ec61bd-ffffffff81ec61d6: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81aafd90)
Location: drivers/char/tpm/tpm_tis.c:123
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81aafd90-ffffffff81aafe50: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81afbbf0)
Location: drivers/char/tpm/tpm_tis.c:226
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81afbbf0-ffffffff81afbcb0: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81b4f280)
Location: drivers/char/tpm/tpm_tis.c:138
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81b4f280-ffffffff81b4f340: check_acpi_tpm2 (STB_LOCAL)
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
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffff8000108c28d0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffff8000108c28d0-ffff8000108c2990: check_acpi_tpm2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:126
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:126
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:126
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8169d050-ffffffff8169d0e2: check_acpi_tpm2 (STB_LOCAL)
ffffffff8169d417-ffffffff8169d430: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8167aa40-ffffffff8167aad2: check_acpi_tpm2 (STB_LOCAL)
ffffffff8167ae07-ffffffff8167ae20: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816cb2c0-ffffffff816cb352: check_acpi_tpm2 (STB_LOCAL)
ffffffff816cb687-ffffffff816cb6a0: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_acpi_tpm2(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: drivers/char/tpm/tpm_tis.c:100
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816e5790-ffffffff816e5822: check_acpi_tpm2 (STB_LOCAL)
ffffffff816e5b57-ffffffff816e5b70: check_acpi_tpm2.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
