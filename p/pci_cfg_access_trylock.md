# Function: <code>pci_cfg_access_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142df50)
Location: drivers/pci/access.c:531
Inline: False
```
**Symbols:**

```
ffffffff8142df50-ffffffff8142dfa1: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479340)
Location: drivers/pci/access.c:642
Inline: False
```
**Symbols:**

```
ffffffff81479340-ffffffff81479391: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a6d0)
Location: drivers/pci/access.c:654
Inline: False
```
**Symbols:**

```
ffffffff8149a6d0-ffffffff8149a721: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4270)
Location: drivers/pci/access.c:662
Inline: False
```
**Symbols:**

```
ffffffff814a4270-ffffffff814a42c1: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e2ff0)
Location: drivers/pci/access.c:662
Inline: False
```
**Symbols:**

```
ffffffff814e2ff0-ffffffff814e3041: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512d90)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffffffff81512d90-ffffffff81512de1: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815285f0)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffffffff815285f0-ffffffff81528641: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557880)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffffffff81557880-ffffffff815578cf: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578eb0)
Location: drivers/pci/access.c:293
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81578eb0-ffffffff81578eff: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dec0)
Location: drivers/pci/access.c:289
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8161dec0-ffffffff8161df0f: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816446e0)
Location: drivers/pci/access.c:289
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff816446e0-ffffffff8164472f: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627460)
Location: drivers/pci/access.c:289
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81627460-ffffffff816274af: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696cb0)
Location: drivers/pci/access.c:289
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81696cb0-ffffffff81696cff: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7c90)
Location: drivers/pci/access.c:294
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff817b7c90-ffffffff817b7ce7: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2500)
Location: drivers/pci/access.c:294
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff818d2500-ffffffff818d2557: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915500)
Location: drivers/pci/access.c:294
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81915500-ffffffff81915557: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d470)
Location: drivers/pci/access.c:294
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff8195d470-ffffffff8195d4c7: pci_cfg_access_trylock (STB_GLOBAL)
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
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db550)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffff8000106db550-ffff8000106db610: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c087718c)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
c087718c-c08771e0: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852770)
Location: drivers/pci/access.c:293
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000852770-c000000000852830: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3aa4)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffffffe0004b3aa4-ffffffe0004b3b04: pci_cfg_access_trylock (STB_GLOBAL)
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
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d3d0)
Location: drivers/pci/access.c:293
Inline: False
```
**Symbols:**

```
ffffffff8156d3d0-ffffffff8156d41f: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bb40)
Location: drivers/pci/access.c:293
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8155bb40-ffffffff8155bb8f: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cc00)
Location: drivers/pci/access.c:293
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8156cc00-ffffffff8156cc4f: pci_cfg_access_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_cfg_access_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587100)
Location: drivers/pci/access.c:293
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81587100-ffffffff8158714f: pci_cfg_access_trylock (STB_GLOBAL)
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
