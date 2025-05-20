# Function: <code>pci_ea_read</code>

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
In drivers/pci/pci.c (ffffffff8143763f)
Location: drivers/pci/pci.c:2271
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff8148328f)
Location: drivers/pci/pci.c:2451
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff814a49ef)
Location: drivers/pci/pci.c:2489
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff814aea6b)
Location: drivers/pci/pci.c:2506
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff814ede3b)
Location: drivers/pci/pci.c:2515
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff8151da89)
Location: drivers/pci/pci.c:2589
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff815331e9)
Location: drivers/pci/pci.c:2784
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff81562858)
Location: drivers/pci/pci.c:2899
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff815839f8)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2965
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff81624b00-ffffffff81624cf1: pci_ea_read (STB_LOCAL)
ffffffff8162c8d4-ffffffff8162c9ea: pci_ea_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3132
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff8164a730-ffffffff8164a921: pci_ea_read (STB_LOCAL)
ffffffff81bf7aaf-ffffffff81bf7bc5: pci_ea_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3162
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff8162d320-ffffffff8162d510: pci_ea_read (STB_LOCAL)
ffffffff81be9956-ffffffff81be9a6c: pci_ea_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3204
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff8169c750-ffffffff8169c950: pci_ea_read (STB_LOCAL)
ffffffff81ce42f5-ffffffff81ce440c: pci_ea_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3291
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff817be680-ffffffff817be8b6: pci_ea_read (STB_LOCAL)
ffffffff81eaad06-ffffffff81eaae1f: pci_ea_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da9f0)
Location: drivers/pci/pci.c:3241
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff818da9f0-ffffffff818dad6a: pci_ea_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191dd30)
Location: drivers/pci/pci.c:3279
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff8191dd30-ffffffff8191e0ca: pci_ea_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_ea_read(struct pci_dev *dev, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196a110)
Location: drivers/pci/pci.c:3392
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
```
**Symbols:**

```
ffffffff8196a110-ffffffff8196a4b1: pci_ea_read (STB_LOCAL)
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
In drivers/pci/pci.c (ffff8000106e7b04)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (c0882c64)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (c00000000086244c)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffe0004be1c2)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff81577f18)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff81566658)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff81577748)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
In drivers/pci/pci.c (ffffffff81591c08)
Location: drivers/pci/pci.c:2895
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
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
