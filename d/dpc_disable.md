# Function: <code>dpc_disable</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81664746)
Location: drivers/pci/pcie/dpc.c:293
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
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
In drivers/pci/pcie/dpc.c (ffffffff81646ab6)
Location: drivers/pci/pcie/dpc.c:357
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
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
In drivers/pci/pcie/dpc.c (ffffffff816b8356)
Location: drivers/pci/pcie/dpc.c:357
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff817dc8d0)
Location: drivers/pci/pcie/dpc.c:357
Inline: True
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
```
**Symbols:**

```
ffffffff817dc8d0-ffffffff817dc94f: dpc_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81942170)
Location: drivers/pci/pcie/dpc.c:361
Inline: True
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
```
**Symbols:**

```
ffffffff81942170-ffffffff819421ef: dpc_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198b400)
Location: drivers/pci/pcie/dpc.c:372
Inline: True
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
```
**Symbols:**

```
ffffffff8198b400-ffffffff8198b47f: dpc_disable.isra.0 (STB_LOCAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
