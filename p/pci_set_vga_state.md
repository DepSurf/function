# Function: <code>pci_set_vga_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438830)
Location: drivers/pci/pci.c:4526
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81438830-ffffffff814389c2: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484500)
Location: drivers/pci/pci.c:4847
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81484500-ffffffff81484692: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5bf0)
Location: drivers/pci/pci.c:4855
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff814a5bf0-ffffffff814a5d82: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814afb60)
Location: drivers/pci/pci.c:5013
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff814afb60-ffffffff814afcb1: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ef090)
Location: drivers/pci/pci.c:5037
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff814ef090-ffffffff814ef1e7: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151f170)
Location: drivers/pci/pci.c:5417
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff8151f170-ffffffff8151f2c4: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81535120)
Location: drivers/pci/pci.c:5718
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81535120-ffffffff81535274: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5814
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81564f77-ffffffff81564fb6: pci_set_vga_state.cold (STB_LOCAL)
ffffffff81564470-ffffffff815645b5: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585750)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81585750-ffffffff815858a5: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c3a0)
Location: drivers/pci/pci.c:5965
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff8162c3a0-ffffffff8162c4d8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81652100)
Location: drivers/pci/pci.c:6039
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81652100-ffffffff81652238: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634bb0)
Location: drivers/pci/pci.c:6088
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81634bb0-ffffffff81634ce8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4ca0)
Location: drivers/pci/pci.c:6278
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff816a4ca0-ffffffff816a4dd8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c7150)
Location: drivers/pci/pci.c:6374
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff817c7150-ffffffff817c72a8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4660)
Location: drivers/pci/pci.c:6321
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff818e4660-ffffffff818e47b8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927cb0)
Location: drivers/pci/pci.c:6443
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81927cb0-ffffffff81927e0c: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970450)
Location: drivers/pci/pci.c:6587
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
  - drivers/pci/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81970450-ffffffff819705ac: pci_set_vga_state (STB_GLOBAL)
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
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106ea080)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffff8000106ea080-ffff8000106ea210: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088501c)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
c088501c-c08851b4: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000865290)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
c000000000865290-c0000000008654a8: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004c027e)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffe0004c027e-ffffffe0004c0398: pci_set_vga_state (STB_GLOBAL)
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
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579c70)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81579c70-ffffffff81579dc5: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815683b0)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff815683b0-ffffffff81568505: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815794a0)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff815794a0-ffffffff815795f5: pci_set_vga_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_set_vga_state(struct pci_dev *dev, bool decode, unsigned int command_bits, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593930)
Location: drivers/pci/pci.c:5944
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
  - drivers/gpu/vga/vgaarb.c:__vga_tryget
```
**Symbols:**

```
ffffffff81593930-ffffffff81593a85: pci_set_vga_state (STB_GLOBAL)
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
