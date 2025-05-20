# Function: <code>shpc_init</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153ec20)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8153ec20-ffffffff8153f694: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81556050)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff81556050-ffffffff81556abd: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff81586329-ffffffff81586b23: shpc_init.cold (STB_LOCAL)
ffffffff81585f00-ffffffff81586073: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff815a7d09-ffffffff815a84ff: shpc_init.cold (STB_LOCAL)
ffffffff815a78e0-ffffffff815a7a53: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81650ac2-ffffffff8165119a: shpc_init.cold (STB_LOCAL)
ffffffff816505b0-ffffffff81650723: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81bfd3ec-ffffffff81bfdac5: shpc_init.cold (STB_LOCAL)
ffffffff81673a50-ffffffff81673bc1: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:914
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81bef1db-ffffffff81bef9ce: shpc_init.cold (STB_LOCAL)
ffffffff81655f80-ffffffff816560f1: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:914
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81cea37f-ffffffff81cead69: shpc_init.cold (STB_LOCAL)
ffffffff816c7f40-ffffffff816c80e4: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:914
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81eb1445-ffffffff81eb1dab: shpc_init.cold (STB_LOCAL)
ffffffff817ee010-ffffffff817ee1ce: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:896
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8208fd10-ffffffff8208fe6d: shpc_init.cold (STB_LOCAL)
ffffffff81915670-ffffffff81916136: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:896
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff82110063-ffffffff821101cd: shpc_init.cold (STB_LOCAL)
ffffffff81958c80-ffffffff8195972f: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:896
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff821edd8b-ffffffff821edef5: shpc_init.cold (STB_LOCAL)
ffffffff819a21f0-ffffffff819a2c9f: shpc_init (STB_GLOBAL)
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
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710ac8)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffff800010710ac8-ffff800010711500: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dca84)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffe0004dca84-ffffffe0004dd388: shpc_init (STB_GLOBAL)
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
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff8159b519-ffffffff8159bd0f: shpc_init.cold (STB_LOCAL)
ffffffff8159b0f0-ffffffff8159b263: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff8158a6a9-ffffffff8158ae9f: shpc_init.cold (STB_LOCAL)
ffffffff8158a280-ffffffff8158a3f3: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff8159ba59-ffffffff8159c24f: shpc_init.cold (STB_LOCAL)
ffffffff8159b630-ffffffff8159b7a3: shpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpc_init(struct controller *ctrl, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:919
Inline: False
```
**Symbols:**

```
ffffffff815b5e89-ffffffff815b667f: shpc_init.cold (STB_LOCAL)
ffffffff815b5a60-ffffffff815b5bd3: shpc_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
