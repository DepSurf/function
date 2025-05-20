# Function: <code>mpx_unmap_tables</code>

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
In arch/x86/mm/mpx.c (ffffffff81075f74)
Location: arch/x86/mm/mpx.c:974
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff810774b4)
Location: arch/x86/mm/mpx.c:974
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff8107b064)
Location: arch/x86/mm/mpx.c:973
Inline: True
Inline callers:
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
In arch/x86/mm/mpx.c (ffffffff81079844)
Location: arch/x86/mm/mpx.c:966
Inline: True
Inline callers:
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
In arch/x86/mm/mpx.c (ffffffff8107fa6e)
Location: arch/x86/mm/mpx.c:860
Inline: True
Inline callers:
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
In arch/x86/mm/mpx.c (ffffffff81082b7e)
Location: arch/x86/mm/mpx.c:860
Inline: True
Inline callers:
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
In arch/x86/mm/mpx.c (ffffffff8108972e)
Location: arch/x86/mm/mpx.c:848
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108cc00)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8108cc00-ffffffff8108d093: mpx_unmap_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108d860)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8108d860-ffffffff8108dcf3: mpx_unmap_tables (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c820)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8108c820-ffffffff8108ccb3: mpx_unmap_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b350)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8107b350-ffffffff8107b7e3: mpx_unmap_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c7d0)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8108c7d0-ffffffff8108cc63: mpx_unmap_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108eb40)
Location: arch/x86/mm/mpx.c:848
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8108eb40-ffffffff8108efec: mpx_unmap_tables (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
