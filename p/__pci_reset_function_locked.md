# Function: <code>__pci_reset_function_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438560)
Location: drivers/pci/pci.c:3763
Inline: False
```
**Symbols:**

```
ffffffff81438560-ffffffff81438572: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484210)
Location: drivers/pci/pci.c:4084
Inline: False
```
**Symbols:**

```
ffffffff81484210-ffffffff81484222: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5970)
Location: drivers/pci/pci.c:4122
Inline: False
```
**Symbols:**

```
ffffffff814a5970-ffffffff814a5982: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af680)
Location: drivers/pci/pci.c:4202
Inline: True
Direct callers:
  - drivers/pci/pci.c:__pci_reset_function
```
**Symbols:**

```
ffffffff814af680-ffffffff814af805: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eeba0)
Location: drivers/pci/pci.c:4210
Inline: True
```
**Symbols:**

```
ffffffff814eeba0-ffffffff814eed25: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e900)
Location: drivers/pci/pci.c:4459
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8151e900-ffffffff8151ea94: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815346f0)
Location: drivers/pci/pci.c:4750
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815346f0-ffffffff81534879: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563ba0)
Location: drivers/pci/pci.c:4848
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81563ba0-ffffffff81563d42: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584e80)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81584e80-ffffffff81585022: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162bae0)
Location: drivers/pci/pci.c:5008
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8162bae0-ffffffff8162bc9e: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816517e0)
Location: drivers/pci/pci.c:5076
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff816517e0-ffffffff816519ce: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634250)
Location: drivers/pci/pci.c:5125
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81634250-ffffffff81634436: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169d880)
Location: drivers/pci/pci.c:5323
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff8169d880-ffffffff8169d8fc: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bfce0)
Location: drivers/pci/pci.c:5419
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff817bfce0-ffffffff817bfd64: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dc2a0)
Location: drivers/pci/pci.c:5356
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff818dc2a0-ffffffff818dc324: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191f5d0)
Location: drivers/pci/pci.c:5478
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8191f5d0-ffffffff8191f660: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81967740)
Location: drivers/pci/pci.c:5588
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81967740-ffffffff819677d0: __pci_reset_function_locked (STB_GLOBAL)
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
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9558)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffff8000106e9558-ffff8000106e96f8: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08844d4)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
c08844d4-c088468c: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864470)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000864470-c000000000864674: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf8fa)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffe0004bf8fa-ffffffe0004bfa50: __pci_reset_function_locked (STB_GLOBAL)
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
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815793a0)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815793a0-ffffffff81579542: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567ae0)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81567ae0-ffffffff81567c82: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578bd0)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81578bd0-ffffffff81578d72: __pci_reset_function_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __pci_reset_function_locked(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593090)
Location: drivers/pci/pci.c:4978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81593090-ffffffff8159322a: __pci_reset_function_locked (STB_GLOBAL)
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
