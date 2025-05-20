# Function: <code>__se_compat_sys_migrate_pages</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125a5b5)
Location: mm/mempolicy.c:1579
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff8126e435)
Location: mm/mempolicy.c:1619
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff81289a65)
Location: mm/mempolicy.c:1665
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff812995d5)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cd7a5)
Location: mm/mempolicy.c:1736
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812da035)
Location: mm/mempolicy.c:1712
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff812e1895)
Location: mm/mempolicy.c:1726
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_migrate_pages(long int pid, long int maxnode, long int old_nodes, long int new_nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412d20)
Location: mm/mempolicy.c:1667
Inline: False
```
**Symbols:**

```
c000000000412d20-c000000000412f7c: __se_compat_sys_migrate_pages (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291bb5)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff81283835)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff8128f9c5)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
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
In mm/mempolicy.c (ffffffff8129fe55)
Location: mm/mempolicy.c:1667
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_compat_sys_migrate_pages
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
