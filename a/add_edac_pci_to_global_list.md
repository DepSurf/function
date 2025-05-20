# Function: <code>add_edac_pci_to_global_list</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff8175fa9e)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff817d1b2c)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff8181a8bc)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff818460ac)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff81888e8c)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff818bae3c)
Location: drivers/edac/edac_pci.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_edac_pci_to_global_list(struct edac_pci_ctl_info *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:100
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff8198b510-ffffffff8198b583: add_edac_pci_to_global_list (STB_LOCAL)
ffffffff8198b9c8-ffffffff8198ba25: add_edac_pci_to_global_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_edac_pci_to_global_list(struct edac_pci_ctl_info *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:100
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff8198f100-ffffffff8198f173: add_edac_pci_to_global_list (STB_LOCAL)
ffffffff81c28b12-ffffffff81c28b6f: add_edac_pci_to_global_list.cold (STB_LOCAL)
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
In drivers/edac/edac_pci.c (ffffffff8197377c)
Location: drivers/edac/edac_pci.c:100
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
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
In drivers/edac/edac_pci.c (ffffffff81a1c47c)
Location: drivers/edac/edac_pci.c:100
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81b8553c)
Location: drivers/edac/edac_pci.c:99
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d2459c)
Location: drivers/edac/edac_pci.c:96
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d8d7ac)
Location: drivers/edac/edac_pci.c:96
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81e4505c)
Location: drivers/edac/edac_pci.c:96
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
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
In drivers/edac/edac_pci.c (ffff800010b13468)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (c0bf13fc)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (c000000000c07ef4)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffe0006ffed2)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff81860cbc)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff8182828c)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff818b02ec)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
In drivers/edac/edac_pci.c (ffffffff818cc57c)
Location: drivers/edac/edac_pci.c:100
Inline: True
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
</ul>
