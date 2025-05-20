# Function: <code>pci_do_fixups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81444f50)
Location: drivers/pci/quirks.c:3259
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81444f50-ffffffff814450d2: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81490e80)
Location: drivers/pci/quirks.c:3389
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81490e80-ffffffff81490fe9: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b26f0)
Location: drivers/pci/quirks.c:3508
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff814b26f0-ffffffff814b2859: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bc9e0)
Location: drivers/pci/quirks.c:3554
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff814bc9e0-ffffffff814bcb4a: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fcda0)
Location: drivers/pci/quirks.c:3569
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff814fcda0-ffffffff814fcf08: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152bc90)
Location: drivers/pci/quirks.c:55
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff8152bc90-ffffffff8152bda9: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81542b00)
Location: drivers/pci/quirks.c:57
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81542b00-ffffffff81542c26: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:57
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81572280-ffffffff81572372: pci_do_fixups (STB_LOCAL)
ffffffff81576727-ffffffff8157676c: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff815938d0-ffffffff815939c2: pci_do_fixups (STB_LOCAL)
ffffffff81597e15-ffffffff81597e5a: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
```
**Symbols:**

```
ffffffff81641e70-ffffffff81641f55: pci_do_fixups (STB_LOCAL)
ffffffff8164674a-ffffffff8164678f: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
```
**Symbols:**

```
ffffffff816682d0-ffffffff816683b5: pci_do_fixups (STB_LOCAL)
ffffffff81bfa31b-ffffffff81bfa360: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164a7f8)
Location: drivers/pci/quirks.c:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816be2d8)
Location: drivers/pci/quirks.c:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff817e42f8)
Location: drivers/pci/quirks.c:58
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8190891e)
Location: drivers/pci/quirks.c:58
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194bfaf)
Location: drivers/pci/quirks.c:151
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8199527f)
Location: drivers/pci/quirks.c:151
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fa8d8)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffff8000106fa8d8-ffff8000106faa18: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c0892d78)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
c0892d78-c0892ec8: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c000000000878300)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
c000000000878300-c0000000008784a4: pci_do_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004ca9e2)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffe0004ca9e2-ffffffe0004caaea: pci_do_fixups (STB_LOCAL)
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
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81587760-ffffffff81587852: pci_do_fixups (STB_LOCAL)
ffffffff8158bca5-ffffffff8158bcea: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81576510-ffffffff81576602: pci_do_fixups (STB_LOCAL)
ffffffff8157a7e5-ffffffff8157a82a: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff81587620-ffffffff81587712: pci_do_fixups (STB_LOCAL)
ffffffff8158bb65-ffffffff8158bbaa: pci_do_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_do_fixups(struct pci_dev *dev, struct pci_fixup *f, struct pci_fixup *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:56
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_apply_final_quirks
```
**Symbols:**

```
ffffffff815a1ad0-ffffffff815a1bc2: pci_do_fixups (STB_LOCAL)
ffffffff815a6015-ffffffff815a605a: pci_do_fixups.cold (STB_LOCAL)
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
