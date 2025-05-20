# Function: <code>pci_reassign_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8143d940)
Location: drivers/pci/setup-res.c:316
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8143d940-ffffffff8143da62: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81489750)
Location: drivers/pci/setup-res.c:319
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81489750-ffffffff81489863: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814aaf40)
Location: drivers/pci/setup-res.c:347
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814aaf40-ffffffff814ab053: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814b5240)
Location: drivers/pci/setup-res.c:347
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814b5240-ffffffff814b5358: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f4c40)
Location: drivers/pci/setup-res.c:361
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814f4c40-ffffffff814f4d58: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524cf0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81524cf0-ffffffff81524e08: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153ab70)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8153ab70-ffffffff8153ac88: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8156a76a-ffffffff8156a7f7: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8156a380-ffffffff8156a40d: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8158b73a-ffffffff8158b7c7: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8158b350-ffffffff8158b3dd: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
**Symbols:**

```
ffffffff816327c3-ffffffff81632862: pci_reassign_resource.cold (STB_LOCAL)
ffffffff81632330-ffffffff81632409: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:355
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
**Symbols:**

```
ffffffff81bf849f-ffffffff81bf853e: pci_reassign_resource.cold (STB_LOCAL)
ffffffff81657950-ffffffff81657a29: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:355
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81bea2f0-ffffffff81bea37f: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8163a270-ffffffff8163a2fd: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:355
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81ce5159-ffffffff81ce51e8: pci_reassign_resource.cold (STB_LOCAL)
ffffffff816aaa80-ffffffff816aab0d: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:359
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81eabbec-ffffffff81eabc7e: pci_reassign_resource.cold (STB_LOCAL)
ffffffff817cd9e0-ffffffff817cda61: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ed200)
Location: drivers/pci/setup-res.c:370
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff818ed200-ffffffff818ed319: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff819306f0)
Location: drivers/pci/setup-res.c:370
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff819306f0-ffffffff81930808: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff819790c0)
Location: drivers/pci/setup-res.c:373
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
**Symbols:**

```
ffffffff819790c0-ffffffff81979206: pci_reassign_resource (STB_GLOBAL)
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
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106f02b8)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffff8000106f02b8-ffff8000106f03f4: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088ae20)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
c088ae20-c088af34: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086d850)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
c00000000086d850-c00000000086d9e4: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c3ef4)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffe0004c3ef4-ffffffe0004c3fec: pci_reassign_resource (STB_GLOBAL)
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
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8157f5ba-ffffffff8157f647: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8157f1d0-ffffffff8157f25d: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8156e39a-ffffffff8156e427: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8156dfb0-ffffffff8156e03d: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8157f48a-ffffffff8157f517: pci_reassign_resource.cold (STB_LOCAL)
ffffffff8157f0a0-ffffffff8157f12d: pci_reassign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_reassign_resource(struct pci_dev *dev, int resno, resource_size_t addsize, resource_size_t min_align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8159993a-ffffffff815999c7: pci_reassign_resource.cold (STB_LOCAL)
ffffffff81599550-ffffffff815995dd: pci_reassign_resource (STB_GLOBAL)
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
