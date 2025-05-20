# Function: <code>pci_iov_remove</code>

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
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81544dc0)
Location: drivers/pci/iov.c:581
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81544dc0-ffffffff81544dfe: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155c190)
Location: drivers/pci/iov.c:606
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff8155c190-ffffffff8155c1ce: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:604
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff8158c7f3-ffffffff8158c80b: pci_iov_remove.cold (STB_LOCAL)
ffffffff8158c3b0-ffffffff8158c3df: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff815ae411-ffffffff815ae429: pci_iov_remove.cold (STB_LOCAL)
ffffffff815adf70-ffffffff815adf9f: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:786
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff816576a1-ffffffff816576b9: pci_iov_remove.cold (STB_LOCAL)
ffffffff81657320-ffffffff8165734f: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:787
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81bfdcd2-ffffffff81bfdcea: pci_iov_remove.cold (STB_LOCAL)
ffffffff816778e0-ffffffff8167790f: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:877
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81befbdb-ffffffff81befbf4: pci_iov_remove.cold (STB_LOCAL)
ffffffff81659e90-ffffffff81659eba: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:884
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81ceaffc-ffffffff81ceb015: pci_iov_remove.cold (STB_LOCAL)
ffffffff816cc1c0-ffffffff816cc1ea: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:925
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81eb2022-ffffffff81eb2047: pci_iov_remove.cold (STB_LOCAL)
ffffffff817f28e0-ffffffff817f2922: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191af70)
Location: drivers/pci/iov.c:925
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff8191af70-ffffffff8191afc6: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195e580)
Location: drivers/pci/iov.c:925
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff8195e580-ffffffff8195e5d6: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7be0)
Location: drivers/pci/iov.c:927
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff819a7be0-ffffffff819a7c36: pci_iov_remove (STB_GLOBAL)
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
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff800010717ee8)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffff800010717ee8-ffff800010717f3c: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a2608)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
c08a2608-c08a2654: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c0000000008888e0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
c0000000008888e0-c000000000888944: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e10c4)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffe0004e10c4-ffffffe0004e111c: pci_iov_remove (STB_GLOBAL)
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
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff815a1bd2-ffffffff815a1bea: pci_iov_remove.cold (STB_LOCAL)
ffffffff815a1730-ffffffff815a175f: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff81590d71-ffffffff81590d89: pci_iov_remove.cold (STB_LOCAL)
ffffffff815908d0-ffffffff815908ff: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff815a2161-ffffffff815a2179: pci_iov_remove.cold (STB_LOCAL)
ffffffff815a1cc0-ffffffff815a1cef: pci_iov_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_iov_remove(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:770
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
**Symbols:**

```
ffffffff815bc561-ffffffff815bc579: pci_iov_remove.cold (STB_LOCAL)
ffffffff815bc0c0-ffffffff815bc0ef: pci_iov_remove (STB_GLOBAL)
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
