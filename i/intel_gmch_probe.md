# Function: <code>intel_gmch_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81522c50)
Location: drivers/char/agp/intel-gtt.c:1344
Inline: True
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81522c50-ffffffff81522edb: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81575ba0)
Location: drivers/char/agp/intel-gtt.c:1354
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81575ba0-ffffffff81575e15: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff815a2230)
Location: drivers/char/agp/intel-gtt.c:1356
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff815a2230-ffffffff815a24a8: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff815b5250)
Location: drivers/char/agp/intel-gtt.c:1357
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff815b5250-ffffffff815b5cf1: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff8161c230)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8161c230-ffffffff8161cd5b: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81655ee0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81655ee0-ffffffff816569f8: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81673de0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81673de0-ffffffff816747a8: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff816aa5d1-ffffffff816aa5f3: intel_gmch_probe.cold (STB_LOCAL)
ffffffff816a9e90-ffffffff816aa082: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff816cd312-ffffffff816cd334: intel_gmch_probe.cold (STB_LOCAL)
ffffffff816ccbd0-ffffffff816ccdc2: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1363
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff817821d1-ffffffff817821f3: intel_gmch_probe.cold (STB_LOCAL)
ffffffff817819e0-ffffffff81781c09: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1363
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81c0a12a-ffffffff81c0a14c: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81799750-ffffffff81799979: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1363
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81bfbb90-ffffffff81bfbbb2: intel_gmch_probe.cold (STB_LOCAL)
ffffffff8177bac0-ffffffff8177bceb: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1363
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81cfc78a-ffffffff81cfc7f7: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81801b50-ffffffff81801e86: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1364
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81ec4fa8-ffffffff81ec5024: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81941270-ffffffff819415e2: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1361
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff82096a6e-ffffffff82096acc: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81aa3fc0-ffffffff81aa434a: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1361
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8211799c-ffffffff821179f9: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81aef8a0-ffffffff81aefc65: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1361
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff821f5711-ffffffff821f576e: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81b42de0-ffffffff81b431a5: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81692d61-ffffffff81692d83: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81692620-ffffffff81692812: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81670752-ffffffff81670774: intel_gmch_probe.cold (STB_LOCAL)
ffffffff81670010-ffffffff81670202: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff816c0fd2-ffffffff816c0ff4: intel_gmch_probe.cold (STB_LOCAL)
ffffffff816c0890-ffffffff816c0a82: intel_gmch_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_gmch_probe(struct pci_dev *bridge_pdev, struct pci_dev *gpu_pdev, struct agp_bridge_data *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:1359
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff816db5a2-ffffffff816db5c4: intel_gmch_probe.cold (STB_LOCAL)
ffffffff816dae60-ffffffff816db052: intel_gmch_probe (STB_GLOBAL)
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
