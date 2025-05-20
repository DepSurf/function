# Function: <code>tpm_tis_core_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c450)
Location: drivers/char/tpm/tpm_tis_core.c:652
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff8157c450-ffffffff8157ca7e: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8900)
Location: drivers/char/tpm/tpm_tis_core.c:680
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff815a8900-ffffffff815a8f31: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be4f0)
Location: drivers/char/tpm/tpm_tis_core.c:678
Inline: False
```
**Symbols:**

```
ffffffff815be4f0-ffffffff815bead1: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624bb0)
Location: drivers/char/tpm/tpm_tis_core.c:750
Inline: False
```
**Symbols:**

```
ffffffff81624bb0-ffffffff8162527f: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165eeb0)
Location: drivers/char/tpm/tpm_tis_core.c:858
Inline: False
```
**Symbols:**

```
ffffffff8165eeb0-ffffffff8165f596: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d360)
Location: drivers/char/tpm/tpm_tis_core.c:854
Inline: False
```
**Symbols:**

```
ffffffff8167d360-ffffffff8167da52: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff816b4348-ffffffff816b4791: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff816b3e00-ffffffff816b40b2: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff816d7028-ffffffff816d7471: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff816d6ae0-ffffffff816d6d92: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:935
Inline: False
```
**Symbols:**

```
ffffffff8178b695-ffffffff8178b95b: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff8178ae10-ffffffff8178b0ae: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:912
Inline: False
```
**Symbols:**

```
ffffffff81c0adbb-ffffffff81c0b0a2: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff817a1c50-ffffffff817a1efd: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:921
Inline: False
```
**Symbols:**

```
ffffffff81bfc707-ffffffff81bfcb1e: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff81784950-ffffffff81784bee: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:922
Inline: False
```
**Symbols:**

```
ffffffff81cfd4a7-ffffffff81cfd8bf: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff8180b3f0-ffffffff8180b712: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:922
Inline: False
```
**Symbols:**

```
ffffffff81ec5d71-ffffffff81ec61bd: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff8194b820-ffffffff8194bbc3: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf3a0)
Location: drivers/char/tpm/tpm_tis_core.c:940
Inline: False
```
**Symbols:**

```
ffffffff81aaf3a0-ffffffff81aafc1b: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb240)
Location: drivers/char/tpm/tpm_tis_core.c:1074
Inline: False
```
**Symbols:**

```
ffffffff81afb240-ffffffff81afba88: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4e8d0)
Location: drivers/char/tpm/tpm_tis_core.c:1102
Inline: False
```
**Symbols:**

```
ffffffff81b4e8d0-ffffffff81b4f118: tpm_tis_core_init (STB_GLOBAL)
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
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c17e0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffff8000108c17e0-ffff8000108c1ea0: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09ba584)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
c09ba584-c09bac6c: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000964410)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
c000000000964410-c000000000964c30: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005730b6)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffe0005730b6-ffffffe0005736b6: tpm_tis_core_init (STB_GLOBAL)
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
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff8169ca78-ffffffff8169cec1: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff8169c530-ffffffff8169c7e2: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff8167a468-ffffffff8167a8b1: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff81679f20-ffffffff8167a1d2: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff816cace8-ffffffff816cb131: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff816ca7a0-ffffffff816caa52: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_tis_core_init(struct device *dev, struct tpm_tis_data *priv, int irq, const struct tpm_tis_phy_ops *phy_ops, acpi_handle acpi_dev_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:853
Inline: False
```
**Symbols:**

```
ffffffff816e51b8-ffffffff816e5601: tpm_tis_core_init.cold (STB_LOCAL)
ffffffff816e4c70-ffffffff816e4f22: tpm_tis_core_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
