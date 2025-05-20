# Function: <code>ata_port_detach</code>

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
In drivers/ata/libata-core.c (ffffffff815c8eab)
Location: drivers/ata/libata-core.c:6264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8162148b)
Location: drivers/ata/libata-core.c:6463
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8165200b)
Location: drivers/ata/libata-core.c:6505
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8166664b)
Location: drivers/ata/libata-core.c:6591
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff816cfcab)
Location: drivers/ata/libata-core.c:6621
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8170c6db)
Location: drivers/ata/libata-core.c:6668
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8172eb5b)
Location: drivers/ata/libata-core.c:6672
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8176a34a)
Location: drivers/ata/libata-core.c:6657
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8178e3b0)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_port_detach(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81853fa0)
Location: drivers/ata/libata-core.c:5867
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_platform_remove_one
  - drivers/ata/libata-core.c:ata_pci_remove_one
```
**Symbols:**

```
ffffffff81853fa0-ffffffff818540e4: ata_port_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_port_detach(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81864270)
Location: drivers/ata/libata-core.c:5867
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_platform_remove_one
  - drivers/ata/libata-core.c:ata_pci_remove_one
```
**Symbols:**

```
ffffffff81864270-ffffffff818643b4: ata_port_detach (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8184616b)
Location: drivers/ata/libata-core.c:5867
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff818d2b8d)
Location: drivers/ata/libata-core.c:5927
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff81a232bd)
Location: drivers/ata/libata-core.c:5895
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff81ba509d)
Location: drivers/ata/libata-core.c:5901
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff81bfbeed)
Location: drivers/ata/libata-core.c:6127
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_port_detach(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c51b30)
Location: drivers/ata/libata-core.c:6083
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_platform_remove_one
  - drivers/ata/libata-core.c:ata_pci_remove_one
```
**Symbols:**

```
ffffffff81c51b30-ffffffff81c51e4e: ata_port_detach (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff800010998918)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (c0a67b28)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (c000000000a5a4cc)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffe0005f8900)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8175353e)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff817333de)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff81783230)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
In drivers/ata/libata-core.c (ffffffff8179d0f0)
Location: drivers/ata/libata-core.c:6681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
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
