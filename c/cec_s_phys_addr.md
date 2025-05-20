# Function: <code>cec_s_phys_addr</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81806677)
Location: drivers/media/cec/cec-adap.c:1546
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
```
**Symbols:**

```
ffffffff818066d0-ffffffff81806728: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81846413)
Location: drivers/media/cec/cec-adap.c:1591
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81846350-ffffffff818463b3: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff818463c0-ffffffff818463e5: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877d53)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81877c90-ffffffff81877cf3: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff81877d00-ffffffff81877d25: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abf81c)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffff800010abf728-ffff800010abf7a0: cec_s_phys_addr.part.0 (STB_LOCAL)
ffff800010abf7a0-ffff800010abf7f0: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba151c)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c0ba144c-c0ba14bc: cec_s_phys_addr.part.0 (STB_LOCAL)
c0ba14bc-c0ba14e8: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba13b8)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c000000000ba12a0-c000000000ba1348: cec_s_phys_addr.part.0 (STB_LOCAL)
c000000000ba1350-c000000000ba1378: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c10d2)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffe0006c0ff8-ffffffe0006c1068: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffe0006c1068-ffffffe0006c10aa: cec_s_phys_addr (STB_GLOBAL)
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
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818202c3)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81820200-ffffffff81820263: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff81820270-ffffffff81820295: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e7963)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff817e78a0-ffffffff817e7903: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff817e7910-ffffffff817e7935: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186d203)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8186d140-ffffffff8186d1a3: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff8186d1b0-ffffffff8186d1d5: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81887193)
Location: drivers/media/cec/cec-adap.c:1605
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-core.c:cec_cec_notify
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff818870d0-ffffffff81887133: cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff81887140-ffffffff81887165: cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
