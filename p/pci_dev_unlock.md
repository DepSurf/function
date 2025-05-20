# Function: <code>pci_dev_unlock</code>

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
In drivers/pci/pci.c (ffffffff81434be7)
Location: drivers/pci/pci.c:3655
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814805c9)
Location: drivers/pci/pci.c:3976
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814a1c19)
Location: drivers/pci/pci.c:4014
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814acfda)
Location: drivers/pci/pci.c:4101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814ec3aa)
Location: drivers/pci/pci.c:4138
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
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
In drivers/pci/pci.c (ffffffff8151bfbc)
Location: drivers/pci/pci.c:4387
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81533d4a)
Location: drivers/pci/pci.c:4678
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8155f51b)
Location: drivers/pci/pci.c:4775
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8158065b)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8162c0b9)
Location: drivers/pci/pci.c:4935
Inline: True
Inline callers:
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
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81651e09)
Location: drivers/pci/pci.c:5003
Inline: True
Inline callers:
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
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff816348f9)
Location: drivers/pci/pci.c:5052
Inline: True
Inline callers:
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
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a49e9)
Location: drivers/pci/pci.c:5116
Inline: True
Inline callers:
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
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff8169d720-ffffffff8169d748: pci_dev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6e49)
Location: drivers/pci/pci.c:5212
Inline: True
Inline callers:
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
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff817bfb60-ffffffff817bfb8a: pci_dev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e42ee)
Location: drivers/pci/pci.c:5149
Inline: True
Inline callers:
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
```
**Symbols:**

```
ffffffff818dc0f0-ffffffff818dc11a: pci_dev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924b02)
Location: drivers/pci/pci.c:5271
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8191f410-ffffffff8191f43a: pci_dev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_unlock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d1d2)
Location: drivers/pci/pci.c:5381
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81967580-ffffffff819675aa: pci_dev_unlock (STB_GLOBAL)
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
In drivers/pci/pci.c (ffff8000106e3144)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (c087f00c)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (c00000000085cf84)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffe0004baa08)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81574b7b)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff815632db)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff815743ab)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8158e88b)
Location: drivers/pci/pci.c:4905
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
