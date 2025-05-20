# Function: <code>__vga_set_legacy_decoding</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8153f4d0)
Location: drivers/gpu/vga/vgaarb.c:684
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
**Symbols:**

```
ffffffff8153f4d0-ffffffff8153f66e: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff816402b0)
Location: drivers/gpu/vga/vgaarb.c:684
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff816402b0-ffffffff8164043a: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81670d00)
Location: drivers/gpu/vga/vgaarb.c:765
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81670d00-ffffffff81670e88: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81685370)
Location: drivers/gpu/vga/vgaarb.c:765
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81685370-ffffffff816854f8: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff816eebd0)
Location: drivers/gpu/vga/vgaarb.c:765
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff816eebd0-ffffffff816eed58: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8172b640)
Location: drivers/gpu/vga/vgaarb.c:765
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff8172b640-ffffffff8172b7d6: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8174ddf0)
Location: drivers/gpu/vga/vgaarb.c:765
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff8174ddf0-ffffffff8174df86: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81789c80-ffffffff81789cfd: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff8178b31d-ffffffff8178b32d: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff817ad880-ffffffff817ad8fd: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff817aef38-ffffffff817aef48: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff818738b0-ffffffff8187392d: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81874fab-ffffffff81874fbb: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:813
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81882450-ffffffff818824cd: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81c186bb-ffffffff81c186cb: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81864ca0-ffffffff81864d1d: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81c0a4ad-ffffffff81c0a4bd: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:793
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff818f3fc0-ffffffff818f403d: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81d0f129-ffffffff81d0f139: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (0)
Location: drivers/pci/vgaarb.c:910
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff817f32f0-ffffffff817f337a: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81eb215d-ffffffff81eb2175: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff8191d880)
Location: drivers/pci/vgaarb.c:910
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff8191d880-ffffffff8191d90e: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff81960cf0)
Location: drivers/pci/vgaarb.c:903
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81960cf0-ffffffff81960eb7: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819aa580)
Location: drivers/pci/vgaarb.c:910
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff819aa580-ffffffff819aa60e: __vga_set_legacy_decoding (STB_LOCAL)
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
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffff8000109bfbb8)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffff8000109bfbb8-ffff8000109bfcc4: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c0a8cb2c)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
c0a8cb2c-c0a8cbc4: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c000000000a80360)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
c000000000a80360-c000000000a80448: __vga_set_legacy_decoding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffe0006125c4)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffe0006125c4-ffffffe00061264e: __vga_set_legacy_decoding (STB_LOCAL)
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
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff817723a0-ffffffff8177241d: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81773a58-ffffffff81773a68: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff81752150-ffffffff817521cd: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff81753808-ffffffff81753818: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff817a2700-ffffffff817a277d: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff817a3db8-ffffffff817a3dc8: __vga_set_legacy_decoding.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __vga_set_legacy_decoding(struct pci_dev *pdev, unsigned int decodes, bool userspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (0)
Location: drivers/gpu/vga/vgaarb.c:814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_legacy_decoding
```
**Symbols:**

```
ffffffff817bc580-ffffffff817bc5fd: __vga_set_legacy_decoding (STB_LOCAL)
ffffffff817bdc38-ffffffff817bdc48: __vga_set_legacy_decoding.cold (STB_LOCAL)
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
