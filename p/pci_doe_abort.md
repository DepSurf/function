# Function: <code>pci_doe_abort</code>

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
int pci_doe_abort(struct pci_doe_mb *doe_mb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff8191fd40)
Location: drivers/pci/doe.c:76
Inline: False
Direct callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/pci/doe.c:signal_task_abort
```
**Symbols:**

```
ffffffff8191fd40-ffffffff8191fe65: pci_doe_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_doe_abort(struct pci_doe_mb *doe_mb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819634b0)
Location: drivers/pci/doe.c:112
Inline: False
Direct callers:
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/pci/doe.c:signal_task_abort
```
**Symbols:**

```
ffffffff819634b0-ffffffff819635cd: pci_doe_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_doe_abort(struct pci_doe_mb *doe_mb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819acb30)
Location: drivers/pci/doe.c:112
Inline: False
Direct callers:
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/pci/doe.c:signal_task_abort
```
**Symbols:**

```
ffffffff819acb30-ffffffff819acc4d: pci_doe_abort (STB_LOCAL)
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
