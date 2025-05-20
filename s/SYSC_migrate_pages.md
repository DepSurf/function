# Function: <code>SYSC_migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e16e8)
Location: mm/mempolicy.c:1339
Inline: True
Inline callers:
  - mm/mempolicy.c:SyS_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812000c8)
Location: mm/mempolicy.c:1371
Inline: True
Inline callers:
  - mm/mempolicy.c:SyS_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81211be0)
Location: mm/mempolicy.c:1373
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff81211be0-ffffffff81211eeb: SYSC_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121bbe0)
Location: mm/mempolicy.c:1302
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff8121bbe0-ffffffff8121bf21: SYSC_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81236ee0)
Location: mm/mempolicy.c:1365
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff81236ee0-ffffffff812371e7: SYSC_migrate_pages (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
