# Function: <code>pci_revert_fw_address</code>

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
In drivers/pci/setup-res.c (ffffffff8143d81e)
Location: drivers/pci/setup-res.c:171
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81489638)
Location: drivers/pci/setup-res.c:171
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814aae28)
Location: drivers/pci/setup-res.c:199
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814b511c)
Location: drivers/pci/setup-res.c:199
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff814f4b1c)
Location: drivers/pci/setup-res.c:200
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81524bc0)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8153aa40)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8156a641)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8158b611)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_revert_fw_address(struct resource *res, struct pci_dev *dev, int resno, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8163261b)
Location: drivers/pci/setup-res.c:194
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff8163261b-ffffffff8163270f: pci_revert_fw_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_revert_fw_address(struct resource *res, struct pci_dev *dev, int resno, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81bf82f7)
Location: drivers/pci/setup-res.c:195
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff81bf82f7-ffffffff81bf83eb: pci_revert_fw_address (STB_LOCAL)
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
In drivers/pci/setup-res.c (ffffffff81bea1ca)
Location: drivers/pci/setup-res.c:195
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81ce5033)
Location: drivers/pci/setup-res.c:195
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81eabaa2)
Location: drivers/pci/setup-res.c:199
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff818ed08a)
Location: drivers/pci/setup-res.c:199
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8193056a)
Location: drivers/pci/setup-res.c:199
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81978f20)
Location: drivers/pci/setup-res.c:201
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffff8000106f013c)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (c088acac)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (c00000000086d654)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffe0004c3dc8)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8157f491)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8156e271)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff8157f361)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
In drivers/pci/setup-res.c (ffffffff81599811)
Location: drivers/pci/setup-res.c:194
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
