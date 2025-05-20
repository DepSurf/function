# Function: <code>find_dependents_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff81f6940d)
Location: arch/x86/kernel/pci-iommu_table.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
```
**Symbols:**

```
ffffffff81f6940d-ffffffff81f69433: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff81f912f4)
Location: arch/x86/kernel/pci-iommu_table.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff81f912f4-ffffffff81f9131a: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff81fcc6bd)
Location: arch/x86/kernel/pci-iommu_table.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff81fcc6bd-ffffffff81fcc6e3: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff820ace80)
Location: arch/x86/kernel/pci-iommu_table.c:10
Inline: True
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff820ace80-ffffffff820acea9: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff826b36ee)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: True
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff826b36ee-ffffffff826b3717: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff826dced3)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff826dced3-ffffffff826dcefc: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff8289331b)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff8289331b-ffffffff82893344: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff828aa990)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff828aa990-ffffffff828aa9b9: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff828ada00)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff828ada00-ffffffff828ada29: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff82cd2db5)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff82cd2db5-ffffffff82cd2dde: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff82fbebfc)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff82fbebfc-ffffffff82fbec25: find_dependents_of (STB_LOCAL)
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
In arch/x86/kernel/pci-iommu_table.c (ffffffff831c9293)
Location: arch/x86/kernel/pci-iommu_table.c:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
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
In arch/x86/kernel/pci-iommu_table.c (ffffffff832aa556)
Location: arch/x86/kernel/pci-iommu_table.c:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff8289ba1f)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff8289ba1f-ffffffff8289ba48: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff82893cc5)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff82893cc5-ffffffff82893cee: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff828ae9e2)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff828ae9e2-ffffffff828aea0b: find_dependents_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_table_entry *find_dependents_of(struct iommu_table_entry *start, struct iommu_table_entry *finish, struct iommu_table_entry *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-iommu_table.c (ffffffff828aea10)
Location: arch/x86/kernel/pci-iommu_table.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:check_iommu_entries
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
```
**Symbols:**

```
ffffffff828aea10-ffffffff828aea39: find_dependents_of (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
