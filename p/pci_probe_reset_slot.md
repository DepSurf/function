# Function: <code>pci_probe_reset_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434e30)
Location: drivers/pci/pci.c:4070
Inline: False
```
**Symbols:**

```
ffffffff81434e30-ffffffff81434e45: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814807a0)
Location: drivers/pci/pci.c:4391
Inline: False
```
**Symbols:**

```
ffffffff814807a0-ffffffff814807b5: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1df0)
Location: drivers/pci/pci.c:4429
Inline: False
```
**Symbols:**

```
ffffffff814a1df0-ffffffff814a1e05: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aba60)
Location: drivers/pci/pci.c:4587
Inline: False
```
**Symbols:**

```
ffffffff814aba60-ffffffff814aba75: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ebbe0)
Location: drivers/pci/pci.c:4611
Inline: False
```
**Symbols:**

```
ffffffff814ebbe0-ffffffff814ebbf5: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a140)
Location: drivers/pci/pci.c:4860
Inline: False
```
**Symbols:**

```
ffffffff8151a140-ffffffff8151a155: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534d68)
Location: drivers/pci/pci.c:5151
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff8152fed0-ffffffff8152fee5: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564228)
Location: drivers/pci/pci.c:5251
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff8155f6a0-ffffffff8155f6b5: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585508)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff815807e0-ffffffff815807f5: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c00c)
Location: drivers/pci/pci.c:5411
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff81628920-ffffffff81628935: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651d5c)
Location: drivers/pci/pci.c:5479
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8164eb40-ffffffff8164eb55: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8163484c)
Location: drivers/pci/pci.c:5528
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff81631760-ffffffff81631775: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a493c)
Location: drivers/pci/pci.c:5718
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff816a0ff0-ffffffff816a1005: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6d9c)
Location: drivers/pci/pci.c:5814
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff817c2dd0-ffffffff817c2ded: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e423c)
Location: drivers/pci/pci.c:5751
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff818dfb80-ffffffff818dfb9d: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927945)
Location: drivers/pci/pci.c:5873
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff81922fe0-ffffffff81922ffd: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819700e5)
Location: drivers/pci/pci.c:5983
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff8196b560-ffffffff8196b57d: pci_probe_reset_slot (STB_GLOBAL)
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
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9c44)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffff8000106e3300-ffff8000106e3330: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884bd4)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
c087f180-c087f1a0: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864d60)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c00000000085d1e0-c00000000085d1f8: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bfef4)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffe0004bab4c-ffffffe0004bab78: pci_probe_reset_slot (STB_GLOBAL)
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
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579a28)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff81574d00-ffffffff81574d15: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81568168)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81563460-ffffffff81563475: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579258)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81574530-ffffffff81574545: pci_probe_reset_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_probe_reset_slot(struct pci_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815936e8)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8158ea00-ffffffff8158ea15: pci_probe_reset_slot (STB_GLOBAL)
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
