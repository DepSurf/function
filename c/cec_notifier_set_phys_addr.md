# Function: <code>cec_notifier_set_phys_addr</code>

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
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81808c37)
Location: drivers/media/cec/cec-notifier.c:81
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81808bb0-ffffffff81808bef: cec_notifier_set_phys_addr.part.4 (STB_LOCAL)
ffffffff81808bf0-ffffffff81808c09: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8184a8c8)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff8184a810-ffffffff8184a87d: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff8184a880-ffffffff8184a899: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8187c0c8)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff8187c010-ffffffff8187c07d: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff8187c080-ffffffff8187c099: cec_notifier_set_phys_addr (STB_GLOBAL)
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
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffff800010ac3b70)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffff800010ac3a98-ffff800010ac3b08: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffff800010ac3b08-ffff800010ac3b40: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c0ba55c4)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
c0ba550c-c0ba556c: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
c0ba556c-c0ba5590: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c000000000ba6358)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
c000000000ba6230-c000000000ba62f0: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
c000000000ba62f0-c000000000ba630c: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffe0006c46e8)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffe0006c4632-ffffffe0006c468a: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffe0006c468a-ffffffe0006c46be: cec_notifier_set_phys_addr (STB_GLOBAL)
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
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81824638)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81824580-ffffffff818245ed: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff818245f0-ffffffff81824609: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff817ebcd8)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff817ebc20-ffffffff817ebc8d: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff817ebc90-ffffffff817ebca9: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81871578)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff818714c0-ffffffff8187152d: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff81871530-ffffffff81871549: cec_notifier_set_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_notifier_set_phys_addr(struct cec_notifier *n, u16 pa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8188b538)
Location: drivers/media/cec/cec-notifier.c:170
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff8188b480-ffffffff8188b4ed: cec_notifier_set_phys_addr.part.0 (STB_LOCAL)
ffffffff8188b4f0-ffffffff8188b509: cec_notifier_set_phys_addr (STB_GLOBAL)
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
