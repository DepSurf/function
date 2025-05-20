# Function: <code>pci_quirk_nxp_rp_acs</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_quirk_nxp_rp_acs(struct pci_dev *dev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4680
Inline: False
```
**Symbols:**

```
ffffffff816c0140-ffffffff816c0155: pci_quirk_nxp_rp_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_quirk_nxp_rp_acs(struct pci_dev *dev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4693
Inline: False
```
**Symbols:**

```
ffffffff817e58f0-ffffffff817e590b: pci_quirk_nxp_rp_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_quirk_nxp_rp_acs(struct pci_dev *dev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4704
Inline: False
```
**Symbols:**

```
ffffffff8190a7f0-ffffffff8190a80b: pci_quirk_nxp_rp_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_quirk_nxp_rp_acs(struct pci_dev *dev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4814
Inline: False
```
**Symbols:**

```
ffffffff8194dcd0-ffffffff8194dceb: pci_quirk_nxp_rp_acs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_quirk_nxp_rp_acs(struct pci_dev *dev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4845
Inline: False
```
**Symbols:**

```
ffffffff819970a0-ffffffff819970bb: pci_quirk_nxp_rp_acs (STB_LOCAL)
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
