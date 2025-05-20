# Function: <code>C_SYSC_migrate_pages</code>

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
In kernel/compat.c (ffffffff81111bb9)
Location: kernel/compat.c:1107
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_migrate_pages
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
In kernel/compat.c (ffffffff81119319)
Location: kernel/compat.c:1107
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120710)
Location: kernel/compat.c:1115
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_migrate_pages
```
**Symbols:**

```
ffffffff81120710-ffffffff811208de: C_SYSC_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81121010)
Location: kernel/compat.c:555
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_migrate_pages
```
**Symbols:**

```
ffffffff81121010-ffffffff811211ea: C_SYSC_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c680)
Location: kernel/compat.c:531
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_migrate_pages
```
**Symbols:**

```
ffffffff8112c680-ffffffff8112c85a: C_SYSC_migrate_pages (STB_LOCAL)
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
