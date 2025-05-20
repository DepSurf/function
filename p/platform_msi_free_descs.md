# Function: <code>platform_msi_free_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8156cad0)
Location: drivers/base/platform-msi.c:113
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
```
**Symbols:**

```
ffffffff8156cad0-ffffffff8156cb36: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815c1fa0)
Location: drivers/base/platform-msi.c:117
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff815c1fa0-ffffffff815c2037: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815f13f0)
Location: drivers/base/platform-msi.c:117
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff815f13f0-ffffffff815f1487: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81605550)
Location: drivers/base/platform-msi.c:117
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81605550-ffffffff816055e7: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8166d950)
Location: drivers/base/platform-msi.c:117
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8166d950-ffffffff8166d9e7: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816a9390)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff816a9390-ffffffff816a9427: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816c9f70)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff816c9f70-ffffffff816ca007: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81705500)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81705500-ffffffff81705594: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81729790)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81729790-ffffffff81729824: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817e63dd)
Location: drivers/base/platform-msi.c:109
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff817e6050-ffffffff817e60e4: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817fb06d)
Location: drivers/base/platform-msi.c:115
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff817face0-ffffffff817fad74: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817dfced)
Location: drivers/base/platform-msi.c:115
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff817df970-ffffffff817dfa04: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8186b7ec)
Location: drivers/base/platform-msi.c:116
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8186b430-ffffffff8186b4c4: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffff80001091f638)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffff80001091f638-ffff80001091f6ec: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (c0a04810)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
c0a04810-c0a04894: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffe00059e5a2)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffe00059e5a2-ffffffe00059e62c: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816ef570)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff816ef570-ffffffff816ef604: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816c9680)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff816c9680-ffffffff816c9714: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8171cc50)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8171cc50-ffffffff8171cce4: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void platform_msi_free_descs(struct device *dev, int base, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81737fb0)
Location: drivers/base/platform-msi.c:109
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81737fb0-ffffffff81738044: platform_msi_free_descs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int base</code>
</li>
<li>
<b>Param added. </b>
<code>int nvec</code>
</li>
</ul>
</details>
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
