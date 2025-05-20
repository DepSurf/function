# Function: <code>fix_northbridge</code>

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
In drivers/char/agp/amd64-agp.c (ffffffff8151fb7d)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff815729dc)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff8159f068)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff815b2f37)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff81619b77)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff8165389e)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff81671a9e)
Location: drivers/char/agp/amd64-agp.c:270
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff816a7675)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff816ca3b5)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff8177f054)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff8177f054-ffffffff8177f225: fix_northbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff81c09728)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81c09728-ffffffff81c098f9: fix_northbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb0d1)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81bfb0d1-ffffffff81bfb29d: fix_northbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff81cfbc82)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81cfbc82-ffffffff81cfbef4: fix_northbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff81ec441f)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81ec441f-ffffffff81ec4716: fix_northbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/amd64-agp.c (0)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81aa0790-ffffffff81aa0a4b: fix_northbridge (STB_LOCAL)
ffffffff82096950-ffffffff82096a2f: fix_northbridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/amd64-agp.c (0)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81aec0b0-ffffffff81aec322: fix_northbridge (STB_LOCAL)
ffffffff821178b6-ffffffff8211795d: fix_northbridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fix_northbridge(struct pci_dev *nb, struct pci_dev *agp, u16 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/amd64-agp.c (0)
Location: drivers/char/agp/amd64-agp.c:271
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
**Symbols:**

```
ffffffff81b3f5f0-ffffffff81b3f862: fix_northbridge (STB_LOCAL)
ffffffff821f562b-ffffffff821f56d2: fix_northbridge.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/amd64-agp.c (ffffffff8168fe05)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff8166d7f5)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff816be075)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
In drivers/char/agp/amd64-agp.c (ffffffff816d8645)
Location: drivers/char/agp/amd64-agp.c:271
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
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
