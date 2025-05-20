# Function: <code>pci_msi_set_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814310a4)
Location: drivers/pci/pci.h:153
Inline: True
```
```
In drivers/pci/msi.c (ffffffff8145481b)
Location: drivers/pci/pci.h:153
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147cebf)
Location: drivers/pci/pci.h:163
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814a130d)
Location: drivers/pci/pci.h:163
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e432)
Location: drivers/pci/pci.h:163
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814c2eeb)
Location: drivers/pci/pci.h:163
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a82d2)
Location: drivers/pci/pci.h:161
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814cd403)
Location: drivers/pci/pci.h:161
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7312)
Location: drivers/pci/pci.h:162
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8150d943)
Location: drivers/pci/pci.h:162
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81516953)
Location: drivers/pci/pci.h:148
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff81542833)
Location: drivers/pci/pci.h:148
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c393)
Location: drivers/pci/pci.h:157
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff81559bf8)
Location: drivers/pci/pci.h:157
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ad4e)
Location: drivers/pci/pci.h:162
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff81589ca5)
Location: drivers/pci/pci.h:162
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157bdde)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff815ab0d5)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162004f)
Location: drivers/pci/pci.h:188
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
```
```
In drivers/pci/msi.c (ffffffff81653db6)
Location: drivers/pci/pci.h:188
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8165e216)
Location: drivers/pci/msi.c:415
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff81640596)
Location: drivers/pci/msi.c:406
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0bf2)
Location: drivers/pci/msi.c:395
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_set_enable(struct pci_dev *dev, int enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4198)
Location: drivers/pci/msi/msi.c:241
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:pci_restore_msi_state
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff817d3a80-ffffffff817d3b0c: pci_msi_set_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_set_enable(struct pci_dev *dev, int enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5924)
Location: drivers/pci/msi/msi.c:270
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff818f4970-ffffffff818f49fc: pci_msi_set_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_set_enable(struct pci_dev *dev, int enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938d54)
Location: drivers/pci/msi/msi.c:270
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81937da0-ffffffff81937e2c: pci_msi_set_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_set_enable(struct pci_dev *dev, int enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981bb4)
Location: drivers/pci/msi/msi.c:271
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81980c00-ffffffff81980c8c: pci_msi_set_enable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df3ac)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffff800010714868)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b004)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (c089f0f4)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857bf0)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (c0000000008841c4)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7402)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffe0004de252)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815702fe)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8159e8a5)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ea5e)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8158da35)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fb2e)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8159ee25)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158a00e)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff815b9255)
Location: drivers/pci/pci.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
