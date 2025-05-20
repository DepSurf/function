# Function: <code>pci_add_ext_cap_save_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814379b0)
Location: drivers/pci/pci.c:2467
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff814379b0-ffffffff814379ca: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814835d0)
Location: drivers/pci/pci.c:2647
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff814835d0-ffffffff814835ea: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4d30)
Location: drivers/pci/pci.c:2685
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff814a4d30-ffffffff814a4d4a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aed90)
Location: drivers/pci/pci.c:2702
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff814aed90-ffffffff814aedaa: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ee160)
Location: drivers/pci/pci.c:2711
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff814ee160-ffffffff814ee17a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151dde0)
Location: drivers/pci/pci.c:2784
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff8151dde0-ffffffff8151ddfa: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81533540)
Location: drivers/pci/pci.c:2979
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81533540-ffffffff8153355a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562a83)
Location: drivers/pci/pci.c:3094
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81562a20-ffffffff81562a3a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583c23)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81583bc0-ffffffff81583bda: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a6e3)
Location: drivers/pci/pci.c:3160
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8162a610-ffffffff8162a69e: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650b53)
Location: drivers/pci/pci.c:3327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff81650a80-ffffffff81650b0d: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633663)
Location: drivers/pci/pci.c:3357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff81633600-ffffffff8163361a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3803)
Location: drivers/pci/pci.c:3399
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff816a37a0-ffffffff816a37ba: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5ab2)
Location: drivers/pci/pci.c:3486
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff817c5a40-ffffffff817c5a66: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e2d0a)
Location: drivers/pci/pci.c:3436
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff818e2c90-ffffffff818e2cb6: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8192614a)
Location: drivers/pci/pci.c:3474
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff819260d0-ffffffff819260f6: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e8da)
Location: drivers/pci/pci.c:3589
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
**Symbols:**

```
ffffffff8196e860-ffffffff8196e886: pci_add_ext_cap_save_buffer (STB_GLOBAL)
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
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7e78)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffff8000106e7de8-ffff8000106e7e30: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882f28)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
c0882eb8-c0882edc: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000862898)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
c000000000862820-c00000000086283c: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004be522)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffe0004be4ac-ffffffe0004be4e8: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578143)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff815780e0-ffffffff815780fa: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81566883)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81566820-ffffffff8156683a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577973)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81577910-ffffffff8157792a: pci_add_ext_cap_save_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_add_ext_cap_save_buffer(struct pci_dev *dev, u16 cap, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591e33)
Location: drivers/pci/pci.c:3090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81591dd0-ffffffff81591dea: pci_add_ext_cap_save_buffer (STB_GLOBAL)
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
