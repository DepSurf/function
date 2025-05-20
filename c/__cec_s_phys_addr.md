# Function: <code>__cec_s_phys_addr</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81807340)
Location: drivers/media/cec/cec-adap.c:1493
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81807316-ffffffff8180738d: __cec_s_phys_addr.cold.17 (STB_LOCAL)
ffffffff818063e0-ffffffff81806647: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81846377)
Location: drivers/media/cec/cec-adap.c:1538
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81846100-ffffffff81846346: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff818488f9-ffffffff8184896e: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff81847f60-ffffffff81847f8f: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877cb7)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81877a40-ffffffff81877c89: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff8187a145-ffffffff8187a181: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff81879820-ffffffff8187984f: __cec_s_phys_addr (STB_GLOBAL)
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
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abf4f8)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010abf4f8-ffff800010abf724: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffff800010ac1418-ffff800010ac147c: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba11a8)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba11a8-c0ba144c: __cec_s_phys_addr.part.0 (STB_LOCAL)
c0ba31f8-c0ba323c: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0f70)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba0f70-c000000000ba129c: __cec_s_phys_addr.part.0 (STB_LOCAL)
c000000000ba3900-c000000000ba3938: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0e40)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c0e40-ffffffe0006c0ff8: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffe0006c290e-ffffffe0006c2962: __cec_s_phys_addr (STB_GLOBAL)
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
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81820227)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8181ffb0-ffffffff818201f9: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff818226b5-ffffffff818226f1: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff81821d90-ffffffff81821dbf: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e78c7)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817e7650-ffffffff817e7899: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff817e9d55-ffffffff817e9d91: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff817e9430-ffffffff817e945f: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186d167)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186cef0-ffffffff8186d139: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff8186f5f5-ffffffff8186f631: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff8186ecd0-ffffffff8186ecff: __cec_s_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __cec_s_phys_addr(struct cec_adapter *adap, u16 phys_addr, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818870f7)
Location: drivers/media/cec/cec-adap.c:1552
Inline: True
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81886e80-ffffffff818870c9: __cec_s_phys_addr.part.0 (STB_LOCAL)
ffffffff81889575-ffffffff818895b1: __cec_s_phys_addr.part.0.cold (STB_LOCAL)
ffffffff81888c50-ffffffff81888c7f: __cec_s_phys_addr (STB_GLOBAL)
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
