# Function: <code>pci_eisa_init</code>

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
In drivers/eisa/pci_eisa.c (ffffffff828ee680)
Location: drivers/eisa/pci_eisa.c:22
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff82909b1a)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff8291351f)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_eisa_init(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/pci_eisa.c (ffffffff82d2609e)
Location: drivers/eisa/pci_eisa.c:21
Inline: False
Direct callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff82d2609e-ffffffff82d26173: pci_eisa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_eisa_init(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/pci_eisa.c (ffffffff8301467a)
Location: drivers/eisa/pci_eisa.c:21
Inline: False
Direct callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8301467a-ffffffff83014752: pci_eisa_init (STB_LOCAL)
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
In drivers/eisa/pci_eisa.c (ffffffff8321f74c)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff83308efb)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff834c2518)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff83f01fc9)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff83727e4d)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff8395be0d)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/eisa/pci_eisa.c (ffffffff828f9333)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff828f0e1c)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff8290db6b)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
In drivers/eisa/pci_eisa.c (ffffffff82914581)
Location: drivers/eisa/pci_eisa.c:21
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
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
