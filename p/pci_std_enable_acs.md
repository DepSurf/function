# Function: <code>pci_std_enable_acs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435e20)
Location: drivers/pci/pci.c:2551
Inline: False
```
**Symbols:**

```
ffffffff81435e20-ffffffff81435ed2: pci_std_enable_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481960)
Location: drivers/pci/pci.c:2731
Inline: False
```
**Symbols:**

```
ffffffff81481960-ffffffff81481a0b: pci_std_enable_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2e30)
Location: drivers/pci/pci.c:2769
Inline: False
```
**Symbols:**

```
ffffffff814a2e30-ffffffff814a2edb: pci_std_enable_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814acc40)
Location: drivers/pci/pci.c:2786
Inline: False
```
**Symbols:**

```
ffffffff814acc40-ffffffff814accdf: pci_std_enable_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec010)
Location: drivers/pci/pci.c:2795
Inline: False
```
**Symbols:**

```
ffffffff814ec010-ffffffff814ec0af: pci_std_enable_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_std_enable_acs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b8e0)
Location: drivers/pci/pci.c:2866
Inline: False
```
**Symbols:**

```
ffffffff8151b8e0-ffffffff8151b97f: pci_std_enable_acs (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff815337c8)
Location: drivers/pci/pci.c:3121
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
In drivers/pci/pci.c (ffffffff81562c9a)
Location: drivers/pci/pci.c:3241
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
In drivers/pci/pci.c (ffffffff81583e2a)
Location: drivers/pci/pci.c:3237
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff8162a897)
Location: drivers/pci/pci.c:3307
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164b2f7)
Location: drivers/pci/pci.c:863
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
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
In drivers/pci/pci.c (ffffffff8162de6a)
Location: drivers/pci/pci.c:893
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
In drivers/pci/pci.c (ffffffff8169fb8d)
Location: drivers/pci/pci.c:903
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
In drivers/pci/pci.c (ffffffff817c197c)
Location: drivers/pci/pci.c:952
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
In drivers/pci/pci.c (ffffffff818de36c)
Location: drivers/pci/pci.c:936
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
In drivers/pci/pci.c (ffffffff819217cc)
Location: drivers/pci/pci.c:950
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
In drivers/pci/pci.c (ffffffff8196972c)
Location: drivers/pci/pci.c:1013
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
In drivers/pci/pci.c (ffff8000106e8124)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (c08831e4)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (c000000000862c38)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (ffffffe0004be748)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (ffffffff8157834a)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (ffffffff81566a8a)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (ffffffff81577b7a)
Location: drivers/pci/pci.c:3237
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
In drivers/pci/pci.c (ffffffff8159203a)
Location: drivers/pci/pci.c:3237
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
