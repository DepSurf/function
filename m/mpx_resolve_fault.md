# Function: <code>mpx_resolve_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpx_resolve_fault(long int *addr, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075090)
Location: arch/x86/mm/mpx.c:543
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff81075090-ffffffff810750e7: mpx_resolve_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpx_resolve_fault(long int *addr, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81076940)
Location: arch/x86/mm/mpx.c:543
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff81076940-ffffffff81076975: mpx_resolve_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b464)
Location: arch/x86/mm/mpx.c:543
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81079bf9)
Location: arch/x86/mm/mpx.c:536
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107fe2c)
Location: arch/x86/mm/mpx.c:430
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81082da0)
Location: arch/x86/mm/mpx.c:430
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81089950)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff8108d067)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108dcc7)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108cc87)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8107b7b7)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108cc37)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108efc0)
Location: arch/x86/mm/mpx.c:418
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
</ul>
