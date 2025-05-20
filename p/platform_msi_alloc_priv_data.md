# Function: <code>platform_msi_alloc_priv_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815c21a0)
Location: drivers/base/platform-msi.c:205
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff815c21a0-ffffffff815c22a3: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815f15f0)
Location: drivers/base/platform-msi.c:204
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff815f15f0-ffffffff815f16f3: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81605750)
Location: drivers/base/platform-msi.c:204
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81605750-ffffffff81605836: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8166db50)
Location: drivers/base/platform-msi.c:204
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8166db50-ffffffff8166dc36: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816a9580)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff816a9580-ffffffff816a9686: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816ca160)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff816ca160-ffffffff816ca266: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81705790)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81705700-ffffffff817057f8: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81705ba9-ffffffff81705bc1: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81729a20)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81729990-ffffffff81729a88: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81729e29-ffffffff81729e41: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817e6270)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff817e61e0-ffffffff817e62d8: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff817e66e9-ffffffff817e6701: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817faf00)
Location: drivers/base/platform-msi.c:202
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff817fae70-ffffffff817faf68: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81c0f9e2-ffffffff81c0f9fa: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817dfb80)
Location: drivers/base/platform-msi.c:202
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff817dfaf0-ffffffff817dfbe8: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81c01b76-ffffffff81c01b8e: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8186b640)
Location: drivers/base/platform-msi.c:203
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8186b5b0-ffffffff8186b6a8: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81d05722-ffffffff81d0573a: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (0)
Location: drivers/base/platform-msi.c:142
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff819b41d0-ffffffff819b42c3: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81ece0b6-ffffffff81ece0cd: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81b290d0)
Location: drivers/base/platform-msi.c:143
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81b290d0-ffffffff81b291d7: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81b79280)
Location: drivers/base/platform-msi.c:143
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81b79280-ffffffff81b79387: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81bcd180)
Location: drivers/base/platform-msi.c:143
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81bcd180-ffffffff81bcd2be: platform_msi_alloc_priv_data (STB_LOCAL)
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
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffff80001091f880)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffff80001091f880-ffff80001091f984: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (c0a049d4)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
c0a049d4-c0a04ac0: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffe00059e75a)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffe00059e75a-ffffffe00059e830: platform_msi_alloc_priv_data (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816ef800)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff816ef770-ffffffff816ef868: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff816efc09-ffffffff816efc21: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816c9910)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff816c9880-ffffffff816c9978: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff816c9d19-ffffffff816c9d31: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8171cee0)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8171ce50-ffffffff8171cf48: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff8171d2e9-ffffffff8171d301: platform_msi_alloc_priv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_msi_priv_data *platform_msi_alloc_priv_data(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81738240)
Location: drivers/base/platform-msi.c:196
Inline: True
Direct callers:
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff817381b0-ffffffff817382a8: platform_msi_alloc_priv_data (STB_LOCAL)
ffffffff81738649-ffffffff81738661: platform_msi_alloc_priv_data.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct platform_msi_priv_data *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
