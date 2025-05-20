# Function: <code>fold_vm_numa_events</code>

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
void fold_vm_numa_events();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c4450)
Location: mm/vmstat.c:793
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff812c4450-ffffffff812c4618: fold_vm_numa_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fold_vm_numa_events();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81321060)
Location: mm/vmstat.c:188
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff81321060-ffffffff81321230: fold_vm_numa_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fold_vm_numa_events();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394fe0)
Location: mm/vmstat.c:187
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff81394fe0-ffffffff813951d7: fold_vm_numa_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fold_vm_numa_events();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7b90)
Location: mm/vmstat.c:188
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff813c7b90-ffffffff813c7df5: fold_vm_numa_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fold_vm_numa_events();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f2570)
Location: mm/vmstat.c:187
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff813f2570-ffffffff813f27d5: fold_vm_numa_events (STB_GLOBAL)
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
