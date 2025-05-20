# Function: <code>pci_setup_bridge_mmio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e080)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff8143e080-ffffffff8143e12e: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81489e80)
Location: drivers/pci/setup-bus.c:627
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81489e80-ffffffff81489f2f: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ab670)
Location: drivers/pci/setup-bus.c:628
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814ab670-ffffffff814ab71f: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b5a40)
Location: drivers/pci/setup-bus.c:619
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814b5a40-ffffffff814b5aed: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f5440)
Location: drivers/pci/setup-bus.c:619
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff814f5440-ffffffff814f54ed: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81526120)
Location: drivers/pci/setup-bus.c:614
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81526120-ffffffff815261cf: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153bfb0)
Location: drivers/pci/setup-bus.c:614
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8153bfb0-ffffffff8153c05f: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8156b850-ffffffff8156b8d1: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff8156e887-ffffffff8156e8be: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8158c830-ffffffff8158c8b1: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff8158f863-ffffffff8158f89a: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:610
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81633890-ffffffff81633911: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff8163739e-ffffffff816373d5: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:611
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81658940-ffffffff816589c1: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff81bf8800-ffffffff81bf8837: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:611
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8163af90-ffffffff8163b011: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff81bea65d-ffffffff81bea694: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:611
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff816ab9a0-ffffffff816aba21: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff81ce54df-ffffffff81ce5516: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:611
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff817ced30-ffffffff817cedc9: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff81eabf9a-ffffffff81eabfd0: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818eea90)
Location: drivers/pci/setup-bus.c:611
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff818eea90-ffffffff818eeb58: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81931f70)
Location: drivers/pci/setup-bus.c:608
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff81931f70-ffffffff81932038: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197aa80)
Location: drivers/pci/setup-bus.c:613
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff8197aa80-ffffffff8197ab5e: pci_setup_bridge_mmio (STB_LOCAL)
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
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f1910)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffff8000106f1910-ffff8000106f19c0: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088c3a0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
c088c3a0-c088c460: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086f4b0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
c00000000086f4b0-c00000000086f590: pci_setup_bridge_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5130)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffe0004c5130-ffffffe0004c51bc: pci_setup_bridge_mmio (STB_LOCAL)
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
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff815806b0-ffffffff81580731: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff815836e7-ffffffff8158371e: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8156f490-ffffffff8156f511: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff815724c3-ffffffff815724fa: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff81580580-ffffffff81580601: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff815835b3-ffffffff815835ea: pci_setup_bridge_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_setup_bridge_mmio(struct pci_dev *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:609
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_setup_bridge
```
**Symbols:**

```
ffffffff8159aa30-ffffffff8159aab1: pci_setup_bridge_mmio (STB_LOCAL)
ffffffff8159da63-ffffffff8159da9a: pci_setup_bridge_mmio.cold (STB_LOCAL)
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
