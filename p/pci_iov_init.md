# Function: <code>pci_iov_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81456bc0)
Location: drivers/pci/iov.c:533
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81456bc0-ffffffff81457188: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814a3810)
Location: drivers/pci/iov.c:529
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814a3810-ffffffff814a3d8f: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814c5470)
Location: drivers/pci/iov.c:532
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814c5470-ffffffff814c59fb: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814cf5d0)
Location: drivers/pci/iov.c:523
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814cf5d0-ffffffff814cfab0: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8150f7e0)
Location: drivers/pci/iov.c:525
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8150f7e0-ffffffff8150fcd0: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81544850)
Location: drivers/pci/iov.c:553
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81544850-ffffffff81544d5f: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155bc20)
Location: drivers/pci/iov.c:578
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8155bc20-ffffffff8155c12c: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:576
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8158c796-ffffffff8158c7f3: pci_iov_init.cold (STB_LOCAL)
ffffffff8158beb0-ffffffff8158c34f: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff815ae3b5-ffffffff815ae411: pci_iov_init.cold (STB_LOCAL)
ffffffff815ada60-ffffffff815adf02: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81657280)
Location: drivers/pci/iov.c:758
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81657280-ffffffff816572bf: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81677840)
Location: drivers/pci/iov.c:759
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81677840-ffffffff81677880: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81659df0)
Location: drivers/pci/iov.c:849
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81659df0-ffffffff81659e30: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cc120)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff816cc120-ffffffff816cc160: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f2820)
Location: drivers/pci/iov.c:897
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff817f2820-ffffffff817f286f: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191ae90)
Location: drivers/pci/iov.c:897
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8191ae90-ffffffff8191aedf: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195e4a0)
Location: drivers/pci/iov.c:897
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8195e4a0-ffffffff8195e4ef: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7b00)
Location: drivers/pci/iov.c:899
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff819a7b00-ffffffff819a7b4f: pci_iov_init (STB_GLOBAL)
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
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff8000107179a0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffff8000107179a0-ffff800010717e80: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a20d4)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c08a20d4-c08a25a8: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c0000000008887d0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c0000000008887d0-c000000000888858: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e0c02)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffe0004e0c02-ffffffe0004e1054: pci_iov_init (STB_GLOBAL)
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
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff815a1b75-ffffffff815a1bd2: pci_iov_init.cold (STB_LOCAL)
ffffffff815a1230-ffffffff815a16cf: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81590d15-ffffffff81590d71: pci_iov_init.cold (STB_LOCAL)
ffffffff815903c0-ffffffff81590862: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff815a2105-ffffffff815a2161: pci_iov_init.cold (STB_LOCAL)
ffffffff815a17b0-ffffffff815a1c52: pci_iov_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_iov_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:742
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff815bc505-ffffffff815bc561: pci_iov_init.cold (STB_LOCAL)
ffffffff815bbbb0-ffffffff815bc052: pci_iov_init (STB_GLOBAL)
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
