# Function: <code>__dev_sort_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143ef20)
Location: drivers/pci/setup-bus.c:193
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8143ef20-ffffffff8143f1a3: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148ad90)
Location: drivers/pci/setup-bus.c:192
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8148ad90-ffffffff8148afbf: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ac580)
Location: drivers/pci/setup-bus.c:193
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814ac580-ffffffff814ac7af: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b68e0)
Location: drivers/pci/setup-bus.c:184
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814b68e0-ffffffff814b6b25: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f5da0)
Location: drivers/pci/setup-bus.c:184
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814f5da0-ffffffff814f5fe5: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:179
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81526a90-ffffffff81526cdb: __dev_sort_resources (STB_LOCAL)
ffffffff8152955f-ffffffff8152956b: __dev_sort_resources.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:179
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8153c930-ffffffff8153cb7b: __dev_sort_resources (STB_LOCAL)
ffffffff8153f412-ffffffff8153f41e: __dev_sort_resources.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8156bff0-ffffffff8156c228: __dev_sort_resources (STB_LOCAL)
ffffffff8156ea17-ffffffff8156ea3e: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8158cfd0-ffffffff8158d208: __dev_sort_resources (STB_LOCAL)
ffffffff8158f9ea-ffffffff8158fa11: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81634a50)
Location: drivers/pci/setup-bus.c:177
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81634a50-ffffffff81634acc: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81659b00)
Location: drivers/pci/setup-bus.c:178
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81659b00-ffffffff81659b7c: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:178
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8163bd90-ffffffff8163bfc5: __dev_sort_resources (STB_LOCAL)
ffffffff81bea7e4-ffffffff81bea812: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:178
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff816ac7c0-ffffffff816aca13: __dev_sort_resources (STB_LOCAL)
ffffffff81ce5666-ffffffff81ce5694: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:178
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff817cfc30-ffffffff817cfe99: __dev_sort_resources (STB_LOCAL)
ffffffff81eac129-ffffffff81eac15e: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818ef9e0)
Location: drivers/pci/setup-bus.c:178
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff818ef9e0-ffffffff818efc71: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81932ef0)
Location: drivers/pci/setup-bus.c:175
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81932ef0-ffffffff819331a3: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197be50)
Location: drivers/pci/setup-bus.c:175
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8197be50-ffffffff8197c132: __dev_sort_resources (STB_LOCAL)
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
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f22b0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffff8000106f22b0-ffff8000106f24f8: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088cd0c)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c088cd0c-c088cf7c: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c0000000008708b0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c0000000008708b0-c000000000870c08: __dev_sort_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5d94)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffe0004c5d94-ffffffe0004c5f9c: __dev_sort_resources (STB_LOCAL)
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
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81580e50-ffffffff81581088: __dev_sort_resources (STB_LOCAL)
ffffffff8158386e-ffffffff81583895: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8156fc30-ffffffff8156fe68: __dev_sort_resources (STB_LOCAL)
ffffffff8157264a-ffffffff81572671: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81580d20-ffffffff81580f58: __dev_sort_resources (STB_LOCAL)
ffffffff8158373a-ffffffff81583761: __dev_sort_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __dev_sort_resources(struct pci_dev *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:176
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8159b1d0-ffffffff8159b408: __dev_sort_resources (STB_LOCAL)
ffffffff8159dbea-ffffffff8159dc11: __dev_sort_resources.cold (STB_LOCAL)
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
