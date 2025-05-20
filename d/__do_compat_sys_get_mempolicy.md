# Function: <code>__do_compat_sys_get_mempolicy</code>

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
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125b6b0)
Location: mm/mempolicy.c:1506
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8125b6b0-ffffffff8125b7e7: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126ff50)
Location: mm/mempolicy.c:1546
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8126ff50-ffffffff81270095: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128b560)
Location: mm/mempolicy.c:1592
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8128b560-ffffffff8128b6a2: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129b0d0)
Location: mm/mempolicy.c:1594
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8129b0d0-ffffffff8129b212: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ce3a0)
Location: mm/mempolicy.c:1663
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812ce3a0-ffffffff812ce4ee: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9330)
Location: mm/mempolicy.c:1639
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812d9330-ffffffff812d947e: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0bc0)
Location: mm/mempolicy.c:1653
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812e0bc0-ffffffff812e0d00: __do_compat_sys_get_mempolicy (STB_LOCAL)
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
In mm/mempolicy.c (ffff800010339cf0)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
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
In mm/mempolicy.c (c000000000414514)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
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
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812936b0)
Location: mm/mempolicy.c:1594
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812936b0-ffffffff812937f2: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812852c0)
Location: mm/mempolicy.c:1594
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812852c0-ffffffff81285402: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812914c0)
Location: mm/mempolicy.c:1594
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812914c0-ffffffff81291602: __do_compat_sys_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int *policy, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a12d0)
Location: mm/mempolicy.c:1594
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812a12d0-ffffffff812a1412: __do_compat_sys_get_mempolicy (STB_LOCAL)
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
