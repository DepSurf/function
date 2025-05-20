# Function: <code>pci_cfg_access_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e910)
Location: drivers/pci/access.c:511
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8142e910-ffffffff8142e95e: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479ee0)
Location: drivers/pci/access.c:622
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81479ee0-ffffffff81479f2e: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149b360)
Location: drivers/pci/access.c:634
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8149b360-ffffffff8149b3ae: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a5040)
Location: drivers/pci/access.c:642
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814a5040-ffffffff814a508e: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3e40)
Location: drivers/pci/access.c:642
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814e3e40-ffffffff814e3e8e: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513830)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81513830-ffffffff81513880: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528f90)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81528f90-ffffffff81528fe0: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81558190)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81558190-ffffffff815581e0: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815797a0)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815797a0-ffffffff815797f0: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e7d0)
Location: drivers/pci/access.c:269
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8161e7d0-ffffffff8161e823: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81645000)
Location: drivers/pci/access.c:269
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81645000-ffffffff81645053: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627d60)
Location: drivers/pci/access.c:269
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81627d60-ffffffff81627db3: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697660)
Location: drivers/pci/access.c:269
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81697660-ffffffff816976b3: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b86a0)
Location: drivers/pci/access.c:274
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff817b86a0-ffffffff817b86f2: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d3050)
Location: drivers/pci/access.c:274
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff818d3050-ffffffff818d30a2: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916050)
Location: drivers/pci/access.c:274
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81916050-ffffffff819160a2: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195dfc0)
Location: drivers/pci/access.c:274
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8195dfc0-ffffffff8195e012: pci_cfg_access_lock (STB_GLOBAL)
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
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106daa20)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffff8000106daa20-ffff8000106daadc: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877b8c)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c0877b8c-c0877c00: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853a70)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c000000000853a70-c000000000853b44: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b4452)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffe0004b4452-ffffffe0004b44f2: pci_cfg_access_lock (STB_GLOBAL)
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
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156dcc0)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8156dcc0-ffffffff8156dd10: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c430)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8155c430-ffffffff8155c47a: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d4f0)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8156d4f0-ffffffff8156d540: pci_cfg_access_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587930)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81587930-ffffffff81587972: pci_cfg_access_lock (STB_GLOBAL)
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
