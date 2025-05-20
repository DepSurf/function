# Function: <code>__pci_assign_resource</code>

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
In drivers/pci/setup-res.c (ffffffff8143d30f)
Location: drivers/pci/setup-res.c:209
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8148919a)
Location: drivers/pci/setup-res.c:209
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814aa97a)
Location: drivers/pci/setup-res.c:237
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814b4c76)
Location: drivers/pci/setup-res.c:237
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814f44b6)
Location: drivers/pci/setup-res.c:251
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff815245d2)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8153a452)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81569e5a)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8158ae2a)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pci_assign_resource(struct pci_bus *bus, struct pci_dev *dev, int resno, resource_size_t size, resource_size_t align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81631f20)
Location: drivers/pci/setup-res.c:245
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff81631f20-ffffffff8163202a: __pci_assign_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pci_assign_resource(struct pci_bus *bus, struct pci_dev *dev, int resno, resource_size_t size, resource_size_t align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81657520)
Location: drivers/pci/setup-res.c:246
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff81657520-ffffffff8165762a: __pci_assign_resource (STB_LOCAL)
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
In drivers/pci/setup-res.c (ffffffff81639efa)
Location: drivers/pci/setup-res.c:246
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff816aa6da)
Location: drivers/pci/setup-res.c:246
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff817cd5d2)
Location: drivers/pci/setup-res.c:250
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff818ecb52)
Location: drivers/pci/setup-res.c:261
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81930032)
Location: drivers/pci/setup-res.c:261
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff819789c2)
Location: drivers/pci/setup-res.c:263
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffff8000106efb48)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (c088a730)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (c00000000086ce58)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffe0004c3908)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8157ecaa)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8156da8a)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8157eb7a)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8159902a)
Location: drivers/pci/setup-res.c:245
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
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
