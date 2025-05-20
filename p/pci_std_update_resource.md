# Function: <code>pci_std_update_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814aaaa0)
Location: drivers/pci/setup-res.c:28
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
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
In drivers/pci/setup-res.c (ffffffff814b4df0)
Location: drivers/pci/setup-res.c:28
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
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
In drivers/pci/setup-res.c (ffffffff814f47f0)
Location: drivers/pci/setup-res.c:29
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
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
In drivers/pci/setup-res.c (ffffffff815248a0)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8153a720)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8156a0d1)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8158b0a1)
Location: drivers/pci/setup-res.c:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:25
Inline: False
```
**Symbols:**

```
ffffffff81631ca0-ffffffff81631e93: pci_std_update_resource (STB_LOCAL)
ffffffff816324fe-ffffffff81632539: pci_std_update_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:25
Inline: False
```
**Symbols:**

```
ffffffff816572a0-ffffffff81657493: pci_std_update_resource (STB_LOCAL)
ffffffff81bf81da-ffffffff81bf8215: pci_std_update_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:25
Inline: False
```
**Symbols:**

```
ffffffff81639c10-ffffffff81639e0a: pci_std_update_resource (STB_LOCAL)
ffffffff81bea07c-ffffffff81bea0b4: pci_std_update_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:25
Inline: False
```
**Symbols:**

```
ffffffff816aa3e0-ffffffff816aa5da: pci_std_update_resource (STB_LOCAL)
ffffffff81ce4e7b-ffffffff81ce4eb3: pci_std_update_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:25
Inline: False
```
**Symbols:**

```
ffffffff817cd280-ffffffff817cd4bd: pci_std_update_resource (STB_LOCAL)
ffffffff81eab905-ffffffff81eab93e: pci_std_update_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ec720)
Location: drivers/pci/setup-res.c:25
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff818ec720-ffffffff818ec991: pci_std_update_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8192fc00)
Location: drivers/pci/setup-res.c:25
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff8192fc00-ffffffff8192fe71: pci_std_update_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_std_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81978580)
Location: drivers/pci/setup-res.c:25
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff81978580-ffffffff819787f9: pci_std_update_resource (STB_LOCAL)
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
In drivers/pci/setup-res.c (ffff8000106efe34)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (c088a9c4)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (c00000000086d200)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffe0004c3b1a)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8157ef21)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8156dd01)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff8157edf1)
Location: drivers/pci/setup-res.c:25
Inline: True
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
In drivers/pci/setup-res.c (ffffffff815992a1)
Location: drivers/pci/setup-res.c:25
Inline: True
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
