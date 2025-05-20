# Function: <code>pci_cfg_access_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e0f0)
Location: drivers/pci/access.c:553
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8142e0f0-ffffffff8142e15a: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814796c0)
Location: drivers/pci/access.c:664
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814796c0-ffffffff8147972a: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149ab50)
Location: drivers/pci/access.c:676
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8149ab50-ffffffff8149abba: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a47d0)
Location: drivers/pci/access.c:684
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814a47d0-ffffffff814a4824: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e35a0)
Location: drivers/pci/access.c:684
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814e35a0-ffffffff814e35f4: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815131c0)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815131c0-ffffffff81513214: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815288b0)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815288b0-ffffffff81528904: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8155865e-ffffffff81558679: pci_cfg_access_unlock.cold (STB_LOCAL)
ffffffff81557b00-ffffffff81557b5c: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579130)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81579130-ffffffff81579184: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e140)
Location: drivers/pci/access.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8161e140-ffffffff8161e197: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644960)
Location: drivers/pci/access.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81644960-ffffffff816449b7: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816276d0)
Location: drivers/pci/access.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff816276d0-ffffffff81627727: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696fd0)
Location: drivers/pci/access.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81696fd0-ffffffff81697027: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8700)
Location: drivers/pci/access.c:316
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff817b8700-ffffffff817b8765: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d30c0)
Location: drivers/pci/access.c:316
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff818d30c0-ffffffff818d3125: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819160c0)
Location: drivers/pci/access.c:316
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff819160c0-ffffffff81916125: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e030)
Location: drivers/pci/access.c:316
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8195e030-ffffffff8195e095: pci_cfg_access_unlock (STB_GLOBAL)
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
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db8e0)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffff8000106db8e0-ffff8000106db9c4: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877c00)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c0877c00-c0877c88: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852c10)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000852c10-c000000000852cac: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3e02)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffe0004b3e02-ffffffe0004b3e70: pci_cfg_access_unlock (STB_GLOBAL)
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
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d650)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8156d650-ffffffff8156d6a4: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bdc0)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8155bdc0-ffffffff8155be14: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156ce80)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8156ce80-ffffffff8156ced4: pci_cfg_access_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587980)
Location: drivers/pci/access.c:315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81587980-ffffffff815879d4: pci_cfg_access_unlock (STB_GLOBAL)
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
