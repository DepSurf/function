# Function: <code>pci_disable_acs_redir</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8153373e)
Location: drivers/pci/pci.c:3065
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81562c0f)
Location: drivers/pci/pci.c:3185
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81583d9f)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_disable_acs_redir(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3251
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81625f40-ffffffff8162605c: pci_disable_acs_redir (STB_LOCAL)
ffffffff8162cadb-ffffffff8162cb0e: pci_disable_acs_redir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_disable_acs_redir(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:807
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8164b1a0-ffffffff8164b29f: pci_disable_acs_redir (STB_LOCAL)
ffffffff81bf7bdd-ffffffff81bf7c10: pci_disable_acs_redir.cold (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff8162dddf)
Location: drivers/pci/pci.c:837
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff8169faf3)
Location: drivers/pci/pci.c:847
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff817c18d2)
Location: drivers/pci/pci.c:896
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff818de2c2)
Location: drivers/pci/pci.c:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81921722)
Location: drivers/pci/pci.c:894
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81969682)
Location: drivers/pci/pci.c:957
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffff8000106e808c)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (c0883140)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (c000000000862b58)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffe0004be6c4)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff815782bf)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff815669ff)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81577aef)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff81591faf)
Location: drivers/pci/pci.c:3181
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
