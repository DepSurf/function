# Function: <code>__pci_set_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434120)
Location: drivers/pci/pci.c:3056
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81434120-ffffffff81434206: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147fab0)
Location: drivers/pci/pci.c:3366
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8147fab0-ffffffff8147fb96: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1100)
Location: drivers/pci/pci.c:3404
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814a1100-ffffffff814a11e6: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aad80)
Location: drivers/pci/pci.c:3542
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814aad80-ffffffff814aae51: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e9fa0)
Location: drivers/pci/pci.c:3557
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814e9fa0-ffffffff814ea071: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519830)
Location: drivers/pci/pci.c:3741
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81519830-ffffffff81519908: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152f290)
Location: drivers/pci/pci.c:4006
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8152f290-ffffffff8152f368: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155ea00)
Location: drivers/pci/pci.c:4104
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8155ea00-ffffffff8155ead1: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157fb60)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8157fb60-ffffffff8157fc31: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627abb)
Location: drivers/pci/pci.c:4171
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81624d80-ffffffff81624e51: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d75b)
Location: drivers/pci/pci.c:4246
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8164a9b0-ffffffff8164aa81: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816302eb)
Location: drivers/pci/pci.c:4278
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8162d590-ffffffff8162d661: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a021b)
Location: drivers/pci/pci.c:4328
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8169caf0-ffffffff8169cbbe: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817be8c0)
Location: drivers/pci/pci.c:4424
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff817be8c0-ffffffff817be9a5: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818de7fb)
Location: drivers/pci/pci.c:4367
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff818dad80-ffffffff818dae65: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81921c5b)
Location: drivers/pci/pci.c:4405
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8191e0e0-ffffffff8191e1c5: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81969dfb)
Location: drivers/pci/pci.c:4515
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_master
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81966160-ffffffff81966245: __pci_set_master (STB_LOCAL)
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
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e26c0)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffff8000106e26c0-ffff8000106e279c: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087e350)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
c087e350-c087e430: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085bfb0)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
c00000000085bfb0-c00000000085c0b4: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba080)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffe0004ba080-ffffffe0004ba134: __pci_set_master (STB_LOCAL)
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
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574080)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81574080-ffffffff81574151: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815627e0)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff815627e0-ffffffff815628b1: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815738b0)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff815738b0-ffffffff81573981: __pci_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pci_set_master(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158dd90)
Location: drivers/pci/pci.c:4100
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8158dd90-ffffffff8158de61: __pci_set_master (STB_LOCAL)
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
