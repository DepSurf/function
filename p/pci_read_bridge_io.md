# Function: <code>pci_read_bridge_io</code>

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
In drivers/pci/probe.c (ffffffff81430a72)
Location: drivers/pci/probe.c:338
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8147c1fd)
Location: drivers/pci/probe.c:341
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8149d75d)
Location: drivers/pci/probe.c:342
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff814a7632)
Location: drivers/pci/probe.c:342
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff814e5f82)
Location: drivers/pci/probe.c:342
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8151543a)
Location: drivers/pci/probe.c:352
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8152ab5a)
Location: drivers/pci/probe.c:351
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8155c8d8)
Location: drivers/pci/probe.c:402
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8157d93a)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_read_bridge_io(struct pci_bus *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622e6a)
Location: drivers/pci/probe.c:398
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff81622e6a-ffffffff81622faf: pci_read_bridge_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_read_bridge_io(struct pci_bus *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81bf7050)
Location: drivers/pci/probe.c:398
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff81bf7050-ffffffff81bf7195: pci_read_bridge_io (STB_LOCAL)
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
In drivers/pci/probe.c (ffffffff81be9009)
Location: drivers/pci/probe.c:399
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff81ce3439)
Location: drivers/pci/probe.c:400
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff81ea9f5e)
Location: drivers/pci/probe.c:399
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff818d5dee)
Location: drivers/pci/probe.c:399
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8191902e)
Location: drivers/pci/probe.c:399
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_read_bridge_io(struct pci_dev *dev, struct resource *res, bool log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8195fbe0)
Location: drivers/pci/probe.c:347
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
```
**Symbols:**

```
ffffffff8195fbe0-ffffffff8195fd62: pci_read_bridge_io (STB_LOCAL)
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
In drivers/pci/probe.c (ffff8000106ddda4)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (c08799c4)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (c000000000856330)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffe0004b6024)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff81571e5a)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff815605ba)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8157168a)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff8158bb6a)
Location: drivers/pci/probe.c:397
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
