# Function: <code>acpi_pci_root_validate_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81485516)
Location: drivers/acpi/pci_root.c:660
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81485516-ffffffff814856ed: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d4133)
Location: drivers/acpi/pci_root.c:660
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff814d4133-ffffffff814d430d: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f6782)
Location: drivers/acpi/pci_root.c:670
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff814f6782-ffffffff814f695c: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81504dc0)
Location: drivers/acpi/pci_root.c:669
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81504dc0-ffffffff81504fe1: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815470e0)
Location: drivers/acpi/pci_root.c:669
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815470e0-ffffffff81547301: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8157d0e0)
Location: drivers/acpi/pci_root.c:678
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff8157d0e0-ffffffff8157d305: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81594f60)
Location: drivers/acpi/pci_root.c:687
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81594f60-ffffffff81595185: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:676
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815c6000-ffffffff815c6181: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815c6be4-ffffffff815c6cbd: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815e7230-ffffffff815e73b1: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815e7e14-ffffffff815e7eed: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:683
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff816928d0-ffffffff81692a4c: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff816937b0-ffffffff81693889: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:681
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff816b0310-ffffffff816b051f: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff81c0183f-ffffffff81c018c2: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:669
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81692900-ffffffff81692afc: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff81bf30d8-ffffffff81bf3138: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81708450-ffffffff8170864c: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff81cefcf7-ffffffff81cefd57: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:854
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff81836790-ffffffff81836995: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff81eb790a-ffffffff81eb7962: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8196a900)
Location: drivers/acpi/pci_root.c:805
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff8196a900-ffffffff8196ab4a: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819b0ec0)
Location: drivers/acpi/pci_root.c:805
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff819b0ec0-ffffffff819b110a: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819fb3a0)
Location: drivers/acpi/pci_root.c:805
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff819fb3a0-ffffffff819fb5ea: acpi_pci_root_validate_resources (STB_LOCAL)
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
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffff800010774470)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffff800010774470-ffff8000107746d0: acpi_pci_root_validate_resources (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815d8510-ffffffff815d8691: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815d90f4-ffffffff815d91cd: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815c2100-ffffffff815c2281: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815c2ce4-ffffffff815c2dbd: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815db510-ffffffff815db691: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815dc0f4-ffffffff815dc1cd: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_pci_root_validate_resources(struct device *dev, struct list_head *resources, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:675
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffffffff815f53d0-ffffffff815f5551: acpi_pci_root_validate_resources (STB_LOCAL)
ffffffff815f5fb4-ffffffff815f608d: acpi_pci_root_validate_resources.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
