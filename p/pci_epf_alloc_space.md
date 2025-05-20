# Function: <code>pci_epf_alloc_space</code>

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
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2ba0)
Location: drivers/pci/endpoint/pci-epf-core.c:122
Inline: False
```
**Symbols:**

```
ffffffff814d2ba0-ffffffff814d2c97: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512fa0)
Location: drivers/pci/endpoint/pci-epf-core.c:122
Inline: False
```
**Symbols:**

```
ffffffff81512fa0-ffffffff8151309a: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81548340)
Location: drivers/pci/endpoint/pci-epf-core.c:115
Inline: False
```
**Symbols:**

```
ffffffff81548340-ffffffff8154848d: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8155e540)
Location: drivers/pci/endpoint/pci-epf-core.c:115
Inline: False
```
**Symbols:**

```
ffffffff8155e540-ffffffff8155e61a: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff8158efa6-ffffffff8158efc2: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff8158e980-ffffffff8158ea72: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff815b0bc6-ffffffff815b0be2: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff815b05a0-ffffffff815b0692: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:105
Inline: False
```
**Symbols:**

```
ffffffff81659e34-ffffffff81659e50: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff816598b0-ffffffff816599a6: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:107
Inline: False
```
**Symbols:**

```
ffffffff81bfdd61-ffffffff81bfdd7d: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff81679c90-ffffffff81679d86: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:153
Inline: False
```
**Symbols:**

```
ffffffff81befc9e-ffffffff81befcb2: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff8165c7e0-ffffffff8165c8ed: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:291
Inline: False
```
**Symbols:**

```
ffffffff81ceb1a2-ffffffff81ceb1dc: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff816ceeb0-ffffffff816cefb7: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:291
Inline: False
```
**Symbols:**

```
ffffffff81eb2610-ffffffff81eb264a: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff817f7b40-ffffffff817f7c60: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:291
Inline: False
```
**Symbols:**

```
ffffffff82090163-ffffffff82090189: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff81923650-ffffffff8192377d: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:259
Inline: False
```
**Symbols:**

```
ffffffff82110501-ffffffff82110527: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff81967260-ffffffff8196738d: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:259
Inline: False
```
**Symbols:**

```
ffffffff821ee229-ffffffff821ee24f: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff819b0990-ffffffff819b0abd: pci_epf_alloc_space (STB_GLOBAL)
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
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071c518)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffff80001071c518-ffff80001071c630: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (c08a57f0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
c08a57f0-c08a58d0: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (c00000000088ca60)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
c00000000088ca60-c00000000088cba8: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e31f2)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffe0004e31f2-ffffffe0004e3306: pci_epf_alloc_space (STB_GLOBAL)
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
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff815a4386-ffffffff815a43a2: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff815a3d60-ffffffff815a3e52: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff81593526-ffffffff81593542: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff81592f00-ffffffff81592ff2: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff815a4916-ffffffff815a4932: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff815a42f0-ffffffff815a43e2: pci_epf_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *pci_epf_alloc_space(struct pci_epf *epf, size_t size, enum pci_barno bar, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:116
Inline: False
```
**Symbols:**

```
ffffffff815bed16-ffffffff815bed32: pci_epf_alloc_space.cold (STB_LOCAL)
ffffffff815be6f0-ffffffff815be7e2: pci_epf_alloc_space (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t align</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pci_epc_interface_type type</code>
</li>
</ul>
</details>
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
