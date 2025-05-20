# Function: <code>get_jump_table_addr</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81082910)
Location: arch/x86/kernel/sev-es.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff81082910-ffffffff81082add: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81084c30)
Location: arch/x86/kernel/sev.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff81084c30-ffffffff81084d6b: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81093df0)
Location: arch/x86/kernel/sev.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff81093df0-ffffffff81093f2b: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83471088)
Location: arch/x86/kernel/sev.c:613
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff83471088-ffffffff8347120f: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e97e50)
Location: arch/x86/kernel/sev.c:613
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff83e97e50-ffffffff83e97fe6: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bb9d0)
Location: arch/x86/kernel/sev.c:625
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff836bb9d0-ffffffff836bbb66: get_jump_table_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_jump_table_addr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ec3b0)
Location: arch/x86/kernel/sev.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
**Symbols:**

```
ffffffff838ec3b0-ffffffff838ec546: get_jump_table_addr (STB_LOCAL)
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
