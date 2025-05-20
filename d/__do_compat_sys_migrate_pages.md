# Function: <code>__do_compat_sys_migrate_pages</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125a3b0)
Location: mm/mempolicy.c:1579
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff8125a3b0-ffffffff8125a583: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126e240)
Location: mm/mempolicy.c:1619
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff8126e240-ffffffff8126e40a: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81289870)
Location: mm/mempolicy.c:1665
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff81289870-ffffffff81289a39: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812993e0)
Location: mm/mempolicy.c:1667
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff812993e0-ffffffff812995a9: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cd5b0)
Location: mm/mempolicy.c:1736
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff812cd5b0-ffffffff812cd779: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9e40)
Location: mm/mempolicy.c:1712
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff812d9e40-ffffffff812da009: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e16b0)
Location: mm/mempolicy.c:1726
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff812e16b0-ffffffff812e186f: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010337f18)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412d74)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
```
</details>
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812919c0)
Location: mm/mempolicy.c:1667
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff812919c0-ffffffff81291b89: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81283640)
Location: mm/mempolicy.c:1667
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff81283640-ffffffff81283809: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128f7d0)
Location: mm/mempolicy.c:1667
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff8128f7d0-ffffffff8128f999: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t *old_nodes, const compat_ulong_t *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129fc60)
Location: mm/mempolicy.c:1667
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
**Symbols:**

```
ffffffff8129fc60-ffffffff8129fe29: __do_compat_sys_migrate_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
