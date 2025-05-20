# Function: <code>pci_vpd_find_id_string</code>

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
int pci_vpd_find_id_string(const u8 *buf, unsigned int len, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff816ab030)
Location: drivers/pci/vpd.c:361
Inline: False
```
**Symbols:**

```
ffffffff816ab030-ffffffff816ab098: pci_vpd_find_id_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_vpd_find_id_string(const u8 *buf, unsigned int len, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ce7e0)
Location: drivers/pci/vpd.c:364
Inline: False
```
**Symbols:**

```
ffffffff817ce7e0-ffffffff817ce870: pci_vpd_find_id_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_vpd_find_id_string(const u8 *buf, unsigned int len, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ee2d0)
Location: drivers/pci/vpd.c:364
Inline: False
```
**Symbols:**

```
ffffffff818ee2d0-ffffffff818ee360: pci_vpd_find_id_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_vpd_find_id_string(const u8 *buf, unsigned int len, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff819317b0)
Location: drivers/pci/vpd.c:364
Inline: False
```
**Symbols:**

```
ffffffff819317b0-ffffffff81931840: pci_vpd_find_id_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_vpd_find_id_string(const u8 *buf, unsigned int len, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8197a3a0)
Location: drivers/pci/vpd.c:394
Inline: False
```
**Symbols:**

```
ffffffff8197a3a0-ffffffff8197a430: pci_vpd_find_id_string (STB_GLOBAL)
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
