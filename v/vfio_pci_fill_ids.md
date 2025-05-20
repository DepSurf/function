# Function: <code>vfio_pci_fill_ids</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8290ca14)
Location: drivers/vfio/pci/vfio_pci.c:1636
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_pci_fill_ids();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff82d215c3)
Location: drivers/vfio/pci/vfio_pci.c:2291
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
**Symbols:**

```
ffffffff82d215c3-ffffffff82d216f9: vfio_pci_fill_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_fill_ids();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8300f3ae)
Location: drivers/vfio/pci/vfio_pci.c:2369
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
**Symbols:**

```
ffffffff8300f3ae-ffffffff8300f4e4: vfio_pci_fill_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_pci_fill_ids();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8321a3e2)
Location: drivers/vfio/pci/vfio_pci.c:2388
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
**Symbols:**

```
ffffffff8321a3e2-ffffffff8321a518: vfio_pci_fill_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_pci_fill_ids();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8330439e)
Location: drivers/vfio/pci/vfio_pci.c:198
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
**Symbols:**

```
ffffffff8330439e-ffffffff833044d4: vfio_pci_fill_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_pci_fill_ids();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff834bd3cc)
Location: drivers/vfio/pci/vfio_pci.c:202
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
**Symbols:**

```
ffffffff834bd3cc-ffffffff834bd529: vfio_pci_fill_ids (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c0000000013b0688)
Location: drivers/vfio/pci/vfio_pci.c:1636
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff828eb89c)
Location: drivers/vfio/pci/vfio_pci.c:1636
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
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
In drivers/vfio/pci/vfio_pci.c (ffffffff82907e0f)
Location: drivers/vfio/pci/vfio_pci.c:1636
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
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
In drivers/vfio/pci/vfio_pci.c (ffffffff8290da76)
Location: drivers/vfio/pci/vfio_pci.c:1636
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
