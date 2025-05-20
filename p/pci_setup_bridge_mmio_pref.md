# Function: <code>pci_setup_bridge_mmio_pref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e130)
Location: drivers/pci/setup-bus.c:647
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff8143e130-ffffffff8143e24e: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81489f30)
Location: drivers/pci/setup-bus.c:646
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81489f30-ffffffff8148a04e: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ab720)
Location: drivers/pci/setup-bus.c:647
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814ab720-ffffffff814ab83e: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b5af0)
Location: drivers/pci/setup-bus.c:638
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814b5af0-ffffffff814b5bfe: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f54f0)
Location: drivers/pci/setup-bus.c:638
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814f54f0-ffffffff814f55fe: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815261d0)
Location: drivers/pci/setup-bus.c:633
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff815261d0-ffffffff815262da: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153c060)
Location: drivers/pci/setup-bus.c:633
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8153c060-ffffffff8153c16a: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8156b8e0-ffffffff8156b99d: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff8156e8be-ffffffff8156e91c: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8158c8c0-ffffffff8158c97d: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff8158f89a-ffffffff8158f8ef: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:629
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81633920-ffffffff816339dd: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff816373d5-ffffffff8163742a: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff816589d0-ffffffff81658a8d: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff81bf8837-ffffffff81bf888c: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8163b020-ffffffff8163b0dd: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff81bea694-ffffffff81bea6e9: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff816aba30-ffffffff816abaed: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff81ce5516-ffffffff81ce556b: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff817cedd0-ffffffff817ceea6: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff81eabfd0-ffffffff81eac024: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818eeb70)
Location: drivers/pci/setup-bus.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff818eeb70-ffffffff818eec9a: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81932050)
Location: drivers/pci/setup-bus.c:627
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff81932050-ffffffff8193217a: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197ab70)
Location: drivers/pci/setup-bus.c:634
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff8197ab70-ffffffff8197acb1: pci_setup_bridge_mmio_pref (STB_LOCAL)
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
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f19c0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffff8000106f19c0-ffff8000106f1ac4: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088c460)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
c088c460-c088c54c: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086f590)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
c00000000086f590-c00000000086f6e4: pci_setup_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c51bc)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffe0004c51bc-ffffffe0004c52a2: pci_setup_bridge_mmio_pref (STB_LOCAL)
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
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81580740-ffffffff815807fd: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff8158371e-ffffffff81583773: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8156f520-ffffffff8156f5dd: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff815724fa-ffffffff8157254f: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81580610-ffffffff815806cd: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff815835ea-ffffffff8158363f: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio_pref(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8159aac0-ffffffff8159ab7d: pci_setup_bridge_mmio_pref (STB_LOCAL)
ffffffff8159da9a-ffffffff8159daef: pci_setup_bridge_mmio_pref.cold (STB_LOCAL)
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
