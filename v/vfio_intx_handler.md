# Function: <code>vfio_intx_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8c30)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff817d8c30-ffffffff817d8ccb: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6a20)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff818a6a20-ffffffff818a6ad6: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5910)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff818b5910-ffffffff818b59c6: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898dc0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff81898dc0-ffffffff81898e7b: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff8192c7d0-ffffffff8192c8bb: vfio_intx_handler (STB_LOCAL)
ffffffff81d12358-ffffffff81d12397: vfio_intx_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff81a82e40-ffffffff81a82f32: vfio_intx_handler (STB_LOCAL)
ffffffff81edd08e-ffffffff81edd0cd: vfio_intx_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8820)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
c000000000ab8820-c000000000ab8950: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782ce0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff81782ce0-ffffffff81782d7b: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdab0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff817cdab0-ffffffff817cdb4b: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7d50)
Location: drivers/vfio/pci/vfio_pci_intrs.c:116
Inline: False
```
**Symbols:**

```
ffffffff817e7d50-ffffffff817e7deb: vfio_intx_handler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
