# Function: <code>pci_vpd_find_ro_info_keyword</code>

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
int pci_vpd_find_ro_info_keyword(const void *buf, unsigned int len, const char *kw, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff816aad40)
Location: drivers/pci/vpd.c:434
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_check_csum
```
**Symbols:**

```
ffffffff816aad40-ffffffff816aae25: pci_vpd_find_ro_info_keyword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_vpd_find_ro_info_keyword(const void *buf, unsigned int len, const char *kw, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817cdcf0)
Location: drivers/pci/vpd.c:463
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_check_csum
```
**Symbols:**

```
ffffffff817cdcf0-ffffffff817cde1b: pci_vpd_find_ro_info_keyword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_vpd_find_ro_info_keyword(const void *buf, unsigned int len, const char *kw, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ed650)
Location: drivers/pci/vpd.c:463
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_check_csum
```
**Symbols:**

```
ffffffff818ed650-ffffffff818ed776: pci_vpd_find_ro_info_keyword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_vpd_find_ro_info_keyword(const void *buf, unsigned int len, const char *kw, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81930b50)
Location: drivers/pci/vpd.c:463
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_check_csum
```
**Symbols:**

```
ffffffff81930b50-ffffffff81930c74: pci_vpd_find_ro_info_keyword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_vpd_find_ro_info_keyword(const void *buf, unsigned int len, const char *kw, unsigned int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81979580)
Location: drivers/pci/vpd.c:493
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_check_csum
```
**Symbols:**

```
ffffffff81979580-ffffffff819796a4: pci_vpd_find_ro_info_keyword (STB_GLOBAL)
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
