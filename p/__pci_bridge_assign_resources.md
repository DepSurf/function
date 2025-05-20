# Function: <code>__pci_bridge_assign_resources</code>

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
In drivers/pci/setup-bus.c (ffffffff81440616)
Location: drivers/pci/setup-bus.c:1427
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff8148c4f6)
Location: drivers/pci/setup-bus.c:1499
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff814adce6)
Location: drivers/pci/setup-bus.c:1500
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff814b8086)
Location: drivers/pci/setup-bus.c:1491
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f81c0)
Location: drivers/pci/setup-bus.c:1491
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff814f81c0-ffffffff814f82a7: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81528d20)
Location: drivers/pci/setup-bus.c:1486
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81528d20-ffffffff81528e07: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153ebc0)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8153ebc0-ffffffff8153eca7: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8156e020-ffffffff8156e101: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8156eae8-ffffffff8156eaf5: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8158f000-ffffffff8158f0e1: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8158fabb-ffffffff8158fac8: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1487
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81636a70-ffffffff81636b51: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff816375f4-ffffffff81637601: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8165bb30-ffffffff8165bc11: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff81bf8a5d-ffffffff81bf8a6a: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8163e0d0-ffffffff8163e1b1: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff81bea8b7-ffffffff81bea8c4: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff816aec30-ffffffff816aed11: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff81ce5739-ffffffff81ce5746: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff817d20b0-ffffffff817d219f: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff81eac209-ffffffff81eac216: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f2550)
Location: drivers/pci/setup-bus.c:1488
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff818f2550-ffffffff818f2632: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81935970)
Location: drivers/pci/setup-bus.c:1481
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81935970-ffffffff81935a52: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197e720)
Location: drivers/pci/setup-bus.c:1491
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8197e720-ffffffff8197e802: __pci_bridge_assign_resources (STB_LOCAL)
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
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f4338)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffff8000106f4338-ffff8000106f4430: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088edb4)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
c088edb4-c088eeac: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000872a00)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
c000000000872a00-c000000000872b24: __pci_bridge_assign_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c74b0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffe0004c74b0-ffffffe0004c757a: __pci_bridge_assign_resources (STB_LOCAL)
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
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81582e80-ffffffff81582f61: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8158393f-ffffffff8158394c: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81571c60-ffffffff81571d41: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8157271b-ffffffff81572728: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81582d50-ffffffff81582e31: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8158380b-ffffffff81583818: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __pci_bridge_assign_resources(const struct pci_dev *bridge, struct list_head *add_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1450
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8159d200-ffffffff8159d2e1: __pci_bridge_assign_resources (STB_LOCAL)
ffffffff8159dcbb-ffffffff8159dcc8: __pci_bridge_assign_resources.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
