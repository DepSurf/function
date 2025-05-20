# Function: <code>find_pci_dr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8143444a)
Location: drivers/pci/pci.c:1454
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_disable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147fea1)
Location: drivers/pci/pci.c:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a14f1)
Location: drivers/pci/pci.c:1500
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab3fc)
Location: drivers/pci/pci.c:1498
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea61c)
Location: drivers/pci/pci.c:1501
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b305)
Location: drivers/pci/pci.c:1556
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff8151aaf0-ffffffff8151ab12: find_pci_dr.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815311b5)
Location: drivers/pci/pci.c:1729
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff81530840-ffffffff81530862: find_pci_dr.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815609f5)
Location: drivers/pci/pci.c:1803
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff815601c0-ffffffff815601e2: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581b15)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff815812f0-ffffffff81581312: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627106)
Location: drivers/pci/pci.c:1869
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164cda6)
Location: drivers/pci/pci.c:2005
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162f926)
Location: drivers/pci/pci.c:2035
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169f636)
Location: drivers/pci/pci.c:2066
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0e8a)
Location: drivers/pci/pci.c:2126
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd69a)
Location: drivers/pci/pci.c:2100
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920b4a)
Location: drivers/pci/pci.c:2138
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968cea)
Location: drivers/pci/pci.c:2235
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_pin_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4cd8)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffff8000106e4288-ffff8000106e42c4: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c08809f0)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
c08800cc-c08800fc: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c00000000085e7b0)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
c00000000085e6d0-c00000000085e718: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc048)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffe0004bb7ce-ffffffe0004bb806: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576035)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff81575810-ffffffff81575832: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564795)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff81563f70-ffffffff81563f92: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575865)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff81575040-ffffffff81575062: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fe35)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
Direct callers:
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
```
**Symbols:**

```
ffffffff8158f610-ffffffff8158f632: find_pci_dr.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
