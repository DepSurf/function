# Function: <code>aer_disable_rootport</code>

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
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144b06f)
Location: drivers/pci/pcie/aer/aerdrv.c:164
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
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
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814972ff)
Location: drivers/pci/pcie/aer/aerdrv.c:164
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
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
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8c5f)
Location: drivers/pci/pcie/aer/aerdrv.c:153
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
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
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814c348f)
Location: drivers/pci/pcie/aer/aerdrv.c:153
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
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
In drivers/pci/pcie/aer/aerdrv.c (ffffffff815036cf)
Location: drivers/pci/pcie/aer/aerdrv.c:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff81533a13)
Location: drivers/pci/pcie/aer.c:1196
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8154af4a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8157ae1a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8159c85a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8163c2c6)
Location: drivers/pci/pcie/aer.c:1261
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816631e0)
Location: drivers/pci/pcie/aer.c:1295
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
```
**Symbols:**

```
ffffffff816631e0-ffffffff81663276: aer_disable_rootport.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816456a0)
Location: drivers/pci/pcie/aer.c:1295
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
```
**Symbols:**

```
ffffffff816456a0-ffffffff81645736: aer_disable_rootport.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816b6890)
Location: drivers/pci/pcie/aer.c:1297
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
```
**Symbols:**

```
ffffffff816b6890-ffffffff816b6926: aer_disable_rootport.isra.0 (STB_LOCAL)
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
In drivers/pci/pcie/aer.c (ffffffff817da440)
Location: drivers/pci/pcie/aer.c:1302
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
```
**Symbols:**

```
ffffffff817da440-ffffffff817da4eb: aer_disable_rootport.isra.0 (STB_LOCAL)
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
In drivers/pci/pcie/aer.c (ffffffff818fbf7f)
Location: drivers/pci/pcie/aer.c:1310
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8193eef0)
Location: drivers/pci/pcie/aer.c:1271
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
```
**Symbols:**

```
ffffffff8193eef0-ffffffff8193ef91: aer_disable_rootport.isra.0 (STB_LOCAL)
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
In drivers/pci/pcie/aer.c (ffffffff819882b8)
Location: drivers/pci/pcie/aer.c:1438
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffff800010704558)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (c089ba74)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d29c2)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8159034a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff8157f22a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff815905aa)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
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
In drivers/pci/pcie/aer.c (ffffffff815aaa5a)
Location: drivers/pci/pcie/aer.c:1336
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
```
</details>
</li>
</ul>

## Differences
