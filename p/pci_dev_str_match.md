# Function: <code>pci_dev_str_match</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152f760)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8152f760-ffffffff8152fa27: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155eec0)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8155eec0-ffffffff8155f189: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580000)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81580000-ffffffff815802c9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625680)
Location: drivers/pci/pci.c:343
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_disable_acs_redir
```
**Symbols:**

```
ffffffff81625680-ffffffff816257f1: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164b020)
Location: drivers/pci/pci.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_disable_acs_redir
```
**Symbols:**

```
ffffffff8164b020-ffffffff8164b191: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162dc30)
Location: drivers/pci/pci.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8162dc30-ffffffff8162dda3: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169d320)
Location: drivers/pci/pci.c:362
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8169d320-ffffffff8169d493: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bf460)
Location: drivers/pci/pci.c:379
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff817bf460-ffffffff817bf619: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dba30)
Location: drivers/pci/pci.c:363
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff818dba30-ffffffff818dbbe9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191eb00)
Location: drivers/pci/pci.c:378
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8191eb00-ffffffff8191ecb9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966c10)
Location: drivers/pci/pci.c:378
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81966c10-ffffffff81966dc9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2ad0)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffff8000106e2ad0-ffff8000106e2db4: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087e738)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
c087e738-c087ea3c: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085c4f0)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
c00000000085c4f0-c00000000085c8f4: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba294)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffe0004ba294-ffffffe0004ba4fa: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574520)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81574520-ffffffff815747e9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562c80)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81562c80-ffffffff81562f49: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81573d50)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff81573d50-ffffffff81574019: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_dev_str_match(struct pci_dev *dev, const char *p, const char **endptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158e230)
Location: drivers/pci/pci.c:311
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_enable_acs
```
**Symbols:**

```
ffffffff8158e230-ffffffff8158e4f9: pci_dev_str_match (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
