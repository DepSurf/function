# Function: <code>quirk_disable_root_port_attributes</code>

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
In drivers/pci/quirks.c (ffffffff8144520c)
Location: drivers/pci/quirks.c:3749
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff8149117c)
Location: drivers/pci/quirks.c:3897
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff814b29ec)
Location: drivers/pci/quirks.c:4016
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff814bcd5d)
Location: drivers/pci/quirks.c:4170
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff814fd11d)
Location: drivers/pci/quirks.c:4163
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152da9c)
Location: drivers/pci/quirks.c:4008
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815448ec)
Location: drivers/pci/quirks.c:4160
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81573e0a)
Location: drivers/pci/quirks.c:4178
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815954ba)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void quirk_disable_root_port_attributes(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4348
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff81643df0-ffffffff81643e58: quirk_disable_root_port_attributes (STB_LOCAL)
ffffffff81646df3-ffffffff81646e4b: quirk_disable_root_port_attributes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void quirk_disable_root_port_attributes(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4295
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff8166a250-ffffffff8166a2b8: quirk_disable_root_port_attributes (STB_LOCAL)
ffffffff81bfa9c4-ffffffff81bfaa1c: quirk_disable_root_port_attributes.cold (STB_LOCAL)
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
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4383
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4424
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4437
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff8190823a)
Location: drivers/pci/quirks.c:4448
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff8194b88a)
Location: drivers/pci/quirks.c:4558
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/quirks.c (ffffffff81996f5a)
Location: drivers/pci/quirks.c:4585
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fc828)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c0894f28)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c00000000087af04)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cc548)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158934a)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81577e8a)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158920a)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815a36ba)
Location: drivers/pci/quirks.c:4272
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
