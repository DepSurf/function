# Function: <code>quirk_no_flr</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81641c80)
Location: drivers/pci/quirks.c:5188
Inline: False
```
**Symbols:**

```
ffffffff81641c80-ffffffff81641c94: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81668060)
Location: drivers/pci/quirks.c:5144
Inline: False
```
**Symbols:**

```
ffffffff81668060-ffffffff81668074: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164a580)
Location: drivers/pci/quirks.c:5234
Inline: False
```
**Symbols:**

```
ffffffff8164a580-ffffffff8164a594: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816bc180)
Location: drivers/pci/quirks.c:5324
Inline: False
```
**Symbols:**

```
ffffffff816bc180-ffffffff816bc194: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff817e0f10)
Location: drivers/pci/quirks.c:5340
Inline: False
```
**Symbols:**

```
ffffffff817e0f10-ffffffff817e0f2a: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81904060)
Location: drivers/pci/quirks.c:5373
Inline: False
```
**Symbols:**

```
ffffffff81904060-ffffffff8190407a: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff819476a0)
Location: drivers/pci/quirks.c:5483
Inline: True
```
**Symbols:**

```
ffffffff819476a0-ffffffff819476ba: quirk_no_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_no_flr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff819909f0)
Location: drivers/pci/quirks.c:5514
Inline: True
```
**Symbols:**

```
ffffffff819909f0-ffffffff81990a0a: quirk_no_flr (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
