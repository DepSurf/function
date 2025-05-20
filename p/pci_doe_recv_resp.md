# Function: <code>pci_doe_recv_resp</code>

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
int pci_doe_recv_resp(struct pci_doe_mb *doe_mb, struct pci_doe_task *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff8191ff00)
Location: drivers/pci/doe.c:165
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff8191ff00-ffffffff81920179: pci_doe_recv_resp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_doe_recv_resp(struct pci_doe_mb *doe_mb, struct pci_doe_task *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff81963960)
Location: drivers/pci/doe.c:212
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff81963960-ffffffff81963c14: pci_doe_recv_resp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_doe_recv_resp(struct pci_doe_mb *doe_mb, struct pci_doe_task *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819ad010)
Location: drivers/pci/doe.c:212
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff819ad010-ffffffff819ad2c4: pci_doe_recv_resp (STB_LOCAL)
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
