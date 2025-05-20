# Function: <code>acpi_dma_controller_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff814be5e0)
Location: drivers/dma/acpi-dma.c:152
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff814be5e0-ffffffff814be8b8: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8150e2d0)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff8150e2d0-ffffffff8150e5b7: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8153a430)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff8153a430-ffffffff8153a717: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8154dc50)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff8154dc50-ffffffff8154df2d: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff815b1330)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff815b1330-ffffffff815b1610: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff815e9760)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff815e9760-ffffffff815e9a31: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81603c40)
Location: drivers/dma/acpi-dma.c:155
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81603c40-ffffffff81603f11: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:152
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff816369e3-ffffffff816369fb: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81636630-ffffffff8163692d: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81658753-ffffffff8165876b: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81658350-ffffffff81658697: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:161
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81708f64-ffffffff81708f98: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81708ae0-ffffffff81708c42: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:161
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81c04569-ffffffff81c0459d: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81725d30-ffffffff81725e92: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:161
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81bf5fee-ffffffff81bf6022: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff817075c0-ffffffff81707722: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:173
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81cf3fff-ffffffff81cf4033: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81782e90-ffffffff81782ff2: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:173
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81ebc161-ffffffff81ebc195: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff818b99e0-ffffffff818b9b54: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a07130)
Location: drivers/dma/acpi-dma.c:173
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81a07130-ffffffff81a072d2: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a4ffc0)
Location: drivers/dma/acpi-dma.c:173
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81a4ffc0-ffffffff81a50162: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a9bc60)
Location: drivers/dma/acpi-dma.c:173
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81a9bc60-ffffffff81a9be31: acpi_dma_controller_register (STB_GLOBAL)
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
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffff8000107feee0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffff8000107feee0-ffff8000107ff234: acpi_dma_controller_register (STB_GLOBAL)
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
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff8161e5f3-ffffffff8161e60b: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff8161e1f0-ffffffff8161e537: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81612ce3-ffffffff81612cfb: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff816128e0-ffffffff81612c27: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff8164c593-ffffffff8164c5ab: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff8164c190-ffffffff8164c4d7: acpi_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_dma_controller_register(struct device *dev, struct dma_chan * (*acpi_dma_xlate)(struct acpi_dma_spec *, struct acpi_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (0)
Location: drivers/dma/acpi-dma.c:159
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
**Symbols:**

```
ffffffff81666b33-ffffffff81666b4b: acpi_dma_controller_register.cold (STB_LOCAL)
ffffffff81666730-ffffffff81666a77: acpi_dma_controller_register (STB_GLOBAL)
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
