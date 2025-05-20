# Function: <code>pci_dev_str_match_path</code>

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
In drivers/pci/pci.c (ffffffff8152f88e)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff8155eff0)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff81580130)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816254c0)
Location: drivers/pci/pci.c:249
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff816254c0-ffffffff8162567f: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164ae60)
Location: drivers/pci/pci.c:258
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff8164ae60-ffffffff8164b01f: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162da60)
Location: drivers/pci/pci.c:258
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff8162da60-ffffffff8162dc23: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169d150)
Location: drivers/pci/pci.c:268
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff8169d150-ffffffff8169d313: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bf270)
Location: drivers/pci/pci.c:285
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff817bf270-ffffffff817bf45b: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818db830)
Location: drivers/pci/pci.c:269
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff818db830-ffffffff818dba1b: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191e900)
Location: drivers/pci/pci.c:284
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff8191e900-ffffffff8191eaeb: pci_dev_str_match_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_dev_str_match_path(struct pci_dev *dev, const char *path, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966a10)
Location: drivers/pci/pci.c:284
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
**Symbols:**

```
ffffffff81966a10-ffffffff81966bfb: pci_dev_str_match_path (STB_LOCAL)
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
In drivers/pci/pci.c (ffff8000106e2c08)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (c087e880)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (c00000000085c6a0)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffe0004ba390)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff81574650)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff81562db0)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff81573e80)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
In drivers/pci/pci.c (ffffffff8158e360)
Location: drivers/pci/pci.c:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
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
