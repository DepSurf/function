# Function: <code>pci_match_one_device</code>

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
In drivers/pci/pci-driver.c (ffffffff8143a36e)
Location: drivers/pci/pci.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_id
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff8143a955)
Location: drivers/pci/pci.h:200
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81486337)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff81486885)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff814a7af7)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff814a8035)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff814b1a91)
Location: drivers/pci/pci.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff814b2015)
Location: drivers/pci/pci.h:208
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff814f1171)
Location: drivers/pci/pci.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff814f1705)
Location: drivers/pci/pci.h:209
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81521077)
Location: drivers/pci/pci.h:195
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff81521995)
Location: drivers/pci/pci.h:195
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81537347)
Location: drivers/pci/pci.h:204
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff815377c5)
Location: drivers/pci/pci.h:204
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81566ca7)
Location: drivers/pci/pci.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff81567155)
Location: drivers/pci/pci.h:209
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81588007)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff815884b5)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff8162e197)
Location: drivers/pci/pci.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff8162f0e5)
Location: drivers/pci/pci.h:239
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816538a7)
Location: drivers/pci/pci.h:220
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff81654765)
Location: drivers/pci/pci.h:220
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636257)
Location: drivers/pci/pci.h:213
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff816371e5)
Location: drivers/pci/pci.h:213
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a6477)
Location: drivers/pci/pci.h:234
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff816a7455)
Location: drivers/pci/pci.h:234
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9129)
Location: drivers/pci/pci.h:195
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff817c9e35)
Location: drivers/pci/pci.h:195
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e6a79)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff818e7895)
Location: drivers/pci/pci.h:210
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192a099)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff8192aeb5)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81972789)
Location: drivers/pci/pci.h:207
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_id
  - drivers/pci/pci-driver.c:pci_match_id
```
```
In drivers/pci/search.c (ffffffff81973745)
Location: drivers/pci/pci.h:207
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffff8000106ec338)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffff8000106ec984)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (c08874e4)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (c0887ba8)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (c000000000867b80)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (c0000000008686a8)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffe0004c145e)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffe0004c18b2)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff8157be97)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff8157c345)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff8156ac67)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff8156b115)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff8157bd57)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff8157c205)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
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
In drivers/pci/pci-driver.c (ffffffff81596049)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:pci_match_device
```
```
In drivers/pci/search.c (ffffffff815966b5)
Location: drivers/pci/pci.h:237
Inline: True
Inline callers:
  - drivers/pci/search.c:match_pci_dev_by_id
```
</details>
</li>
</ul>

## Differences
