# Function: <code>pci_dev_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814359e0)
Location: drivers/pci/pci.c:3644
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814359e0-ffffffff81435a2f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814814c0)
Location: drivers/pci/pci.c:3965
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814814c0-ffffffff8148150f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a29f0)
Location: drivers/pci/pci.c:4003
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814a29f0-ffffffff814a2a3f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac820)
Location: drivers/pci/pci.c:4090
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814ac820-ffffffff814ac86f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb910)
Location: drivers/pci/pci.c:4127
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814eb910-ffffffff814eb95f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b350)
Location: drivers/pci/pci.c:4376
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff8151b350-ffffffff8151b39f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531200)
Location: drivers/pci/pci.c:4667
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81531200-ffffffff8153124f: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560a40)
Location: drivers/pci/pci.c:4764
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81560a40-ffffffff81560a9d: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581b60)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81581b60-ffffffff81581bbd: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628a87)
Location: drivers/pci/pci.c:4924
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164eca7)
Location: drivers/pci/pci.c:4992
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
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
In drivers/pci/pci.c (ffffffff81632368)
Location: drivers/pci/pci.c:5041
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a2638)
Location: drivers/pci/pci.c:5104
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff8169e270-ffffffff8169e2c7: pci_dev_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4722)
Location: drivers/pci/pci.c:5200
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff817bfb10-ffffffff817bfb5e: pci_dev_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1682)
Location: drivers/pci/pci.c:5137
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff818dc090-ffffffff818dc0de: pci_dev_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924ac2)
Location: drivers/pci/pci.c:5259
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff8191f3b0-ffffffff8191f3fe: pci_dev_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d192)
Location: drivers/pci/pci.c:5369
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81967520-ffffffff8196756e: pci_dev_trylock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4d50)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffff8000106e4d50-ffff8000106e4dc8: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880a48)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
c0880a48-c0880a98: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f430)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
c00000000085f430-c00000000085f4f8: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc0b8)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffe0004bc0b8-ffffffe0004bc124: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576080)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff81576080-ffffffff815760dd: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815647e0)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff815647e0-ffffffff8156483d: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815758b0)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff815758b0-ffffffff8157590d: pci_dev_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_dev_trylock(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fe80)
Location: drivers/pci/pci.c:4894
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
**Symbols:**

```
ffffffff8158fe80-ffffffff8158fedd: pci_dev_trylock (STB_LOCAL)
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
