# Function: <code>pci_dev_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff816f66a6)
Location: arch/x86/pci/mmconfig_64.c:18
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff816fa27e)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8175b418)
Location: arch/x86/pci/mmconfig_64.c:18
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8175f100)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81787988)
Location: arch/x86/pci/mmconfig_64.c:18
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8178b630)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff817a6ab8)
Location: arch/x86/pci/mmconfig_64.c:18
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff817aa5c0)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8181dd18)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81821a90)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81867f68)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8186bd40)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81887fe8)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8188be20)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff818d290f)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff818d67a3)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81904cbf)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81908b23)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81bb527f)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81bb9473)
Location: arch/x86/pci/numachip.c:18
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81bca47f)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81bcdd53)
Location: arch/x86/pci/numachip.c:18
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81bbddc8)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81bc170c)
Location: arch/x86/pci/numachip.c:18
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81c8dd08)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81c91cdc)
Location: arch/x86/pci/numachip.c:19
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81e3cc98)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81e411e0)
Location: arch/x86/pci/numachip.c:19
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff82015f68)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8201b760)
Location: arch/x86/pci/numachip.c:19
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff82096348)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8209bdd0)
Location: arch/x86/pci/numachip.c:19
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8216d858)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff82173580)
Location: arch/x86/pci/numachip.c:19
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
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
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff818a40ef)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff818a7ee3)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8185f85f)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff81862a03)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff818f56df)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff818f9543)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff819167bf)
Location: arch/x86/pci/mmconfig_64.c:19
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
```
```
In arch/x86/pci/numachip.c (ffffffff8191a67b)
Location: arch/x86/pci/numachip.c:21
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
</details>
</li>
</ul>

## Differences
