# Function: <code>tpm_tis_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_tis_init(struct device *dev, struct tpm_info *tpm_info, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff815290e0)
Location: drivers/char/tpm/tpm_tis.c:665
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff815290e0-ffffffff81529814: tpm_tis_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_tis_init(struct device *dev, struct tpm_info *tpm_info, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8157cc30)
Location: drivers/char/tpm/tpm_tis.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8157cc30-ffffffff8157ccbd: tpm_tis_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_tis_init(struct device *dev, struct tpm_info *tpm_info, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff815a90f0)
Location: drivers/char/tpm/tpm_tis.c:144
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff815a90f0-ffffffff815a917d: tpm_tis_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff815bf181)
Location: drivers/char/tpm/tpm_tis.c:287
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff815beec0-ffffffff815befc8: tpm_tis_init.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81625781)
Location: drivers/char/tpm/tpm_tis.c:193
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816254a0-ffffffff816255c9: tpm_tis_init.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8165fa91)
Location: drivers/char/tpm/tpm_tis.c:193
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8165f7c0-ffffffff8165f8de: tpm_tis_init.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8167df61)
Location: drivers/char/tpm/tpm_tis.c:193
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8167dc80-ffffffff8167dda1: tpm_tis_init.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff816b4cb1)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816b49c0-ffffffff816b4af4: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff816d7991)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816d76a0-ffffffff816d77d4: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8178be61)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8178bb70-ffffffff8178bca7: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff817a2411)
Location: drivers/char/tpm/tpm_tis.c:212
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff817a2110-ffffffff817a222b: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81785111)
Location: drivers/char/tpm/tpm_tis.c:212
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81784e00-ffffffff81784f26: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8180bc41)
Location: drivers/char/tpm/tpm_tis.c:212
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8180b930-ffffffff8180ba54: tpm_tis_init.part.0 (STB_LOCAL)
ffffffff81cfd8d8-ffffffff81cfd8ed: tpm_tis_init.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8194c1c1)
Location: drivers/char/tpm/tpm_tis.c:205
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8194be90-ffffffff8194bfc7: tpm_tis_init.part.0 (STB_LOCAL)
ffffffff81ec61d6-ffffffff81ec61eb: tpm_tis_init.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81ab02e1)
Location: drivers/char/tpm/tpm_tis.c:206
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81aaff50-ffffffff81ab0087: tpm_tis_init.part.0 (STB_LOCAL)
ffffffff82096c23-ffffffff82096c38: tpm_tis_init.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81afc12f)
Location: drivers/char/tpm/tpm_tis.c:309
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81afbda0-ffffffff81afbed2: tpm_tis_init.part.0 (STB_LOCAL)
ffffffff82117af5-ffffffff82117b0a: tpm_tis_init.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81b4f74f)
Location: drivers/char/tpm/tpm_tis.c:221
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff81b4f430-ffffffff81b4f570: tpm_tis_init.part.0 (STB_LOCAL)
ffffffff821f586a-ffffffff821f5894: tpm_tis_init.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2c94)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffff8000108c2990-ffff8000108c2af4: tpm_tis_init.part.0 (STB_LOCAL)
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
In drivers/char/tpm/tpm_tis.c (c09bb09c)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
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
In drivers/char/tpm/tpm_tis.c (c000000000965204)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
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
In drivers/char/tpm/tpm_tis.c (ffffffe000573af4)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8169d3e1)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8169d0f0-ffffffff8169d224: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff8167add1)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff8167aae0-ffffffff8167ac14: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff816cb651)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816cb360-ffffffff816cb494: tpm_tis_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff816e5b21)
Location: drivers/char/tpm/tpm_tis.c:189
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffffffff816e5830-ffffffff816e5964: tpm_tis_init.part.0 (STB_LOCAL)
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
</ul>
