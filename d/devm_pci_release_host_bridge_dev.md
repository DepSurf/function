# Function: <code>devm_pci_release_host_bridge_dev</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a63ba)
Location: drivers/pci/probe.c:513
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff814a6210-ffffffff814a622b: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e51fa)
Location: drivers/pci/probe.c:513
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff814e5050-ffffffff814e506e: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815146b5)
Location: drivers/pci/probe.c:523
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff81514680-ffffffff815146ad: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81529e15)
Location: drivers/pci/probe.c:522
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff81529de0-ffffffff81529e0d: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815590a5)
Location: drivers/pci/probe.c:572
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff81559070-ffffffff8155909d: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a650)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff8157a650-ffffffff8157a689: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dcf98)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffff8000106dcf98-ffff8000106dcfdc: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0878b10)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
c0878b10-c0878b4c: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008551b0)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
c0000000008551b0-c00000000085521c: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b53b0)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffe0004b53b0-ffffffe0004b53f2: devm_pci_release_host_bridge_dev (STB_LOCAL)
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
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156eb70)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff8156eb70-ffffffff8156eba9: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d2d0)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff8155d2d0-ffffffff8155d309: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e3a0)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff8156e3a0-ffffffff8156e3d9: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devm_pci_release_host_bridge_dev(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81588880)
Location: drivers/pci/probe.c:567
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff81588880-ffffffff815888b9: devm_pci_release_host_bridge_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
