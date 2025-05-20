# Function: <code>alloc_perm_bits</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817db130)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff817db130-ffffffff817db1b7: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9100)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff818a9100-ffffffff818a9187: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8030)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff818b8030-ffffffff818b80b7: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189b400)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff8189b400-ffffffff8189b487: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192f500)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff8192f500-ffffffff8192f587: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a85e90)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff81a85e90-ffffffff81a85f24: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abc150)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
c000000000abc150-c000000000abc22c: alloc_perm_bits (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817851e0)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff817851e0-ffffffff81785267: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cffb0)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff817cffb0-ffffffff817d0037: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_perm_bits(struct perm_bits *perm, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817ea250)
Location: drivers/vfio/pci/vfio_pci_config.c:346
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff817ea250-ffffffff817ea2d7: alloc_perm_bits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
