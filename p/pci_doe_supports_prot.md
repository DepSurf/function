# Function: <code>pci_doe_supports_prot</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_doe_supports_prot(struct pci_doe_mb *doe_mb, u16 vid, u8 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff8191f930)
Location: drivers/pci/doe.c:493
Inline: False
Direct callers:
  - drivers/pci/doe.c:pci_doe_submit_task
```
**Symbols:**

```
ffffffff8191f930-ffffffff8191fa14: pci_doe_supports_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_doe_supports_prot(struct pci_doe_mb *doe_mb, u16 vid, u8 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff81963010)
Location: drivers/pci/doe.c:550
Inline: False
Direct callers:
  - drivers/pci/doe.c:pci_find_doe_mailbox
  - drivers/pci/doe.c:pci_doe
```
**Symbols:**

```
ffffffff81963010-ffffffff819630f4: pci_doe_supports_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_doe_supports_prot(struct pci_doe_mb *doe_mb, u16 vid, u8 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819ac690)
Location: drivers/pci/doe.c:550
Inline: False
Direct callers:
  - drivers/pci/doe.c:pci_find_doe_mailbox
  - drivers/pci/doe.c:pci_doe
```
**Symbols:**

```
ffffffff819ac690-ffffffff819ac774: pci_doe_supports_prot (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
