# Function: <code>C_SYSC_get_mempolicy</code>

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
In mm/mempolicy.c (ffffffff811e195b)
Location: mm/mempolicy.c:1462
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
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
In mm/mempolicy.c (ffffffff8120033b)
Location: mm/mempolicy.c:1494
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81211670)
Location: mm/mempolicy.c:1496
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff81211670-ffffffff812117ab: C_SYSC_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121cf90)
Location: mm/mempolicy.c:1425
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff8121cf90-ffffffff8121d0d2: C_SYSC_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238180)
Location: mm/mempolicy.c:1482
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff81238180-ffffffff812382c2: C_SYSC_get_mempolicy (STB_LOCAL)
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
