# Function: <code>__do_compat_sys_mbind</code>

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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ca40)
Location: mm/mempolicy.c:1557
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff8125ca40-ffffffff8125cb5a: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81271320)
Location: mm/mempolicy.c:1597
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff81271320-ffffffff8127143e: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c930)
Location: mm/mempolicy.c:1643
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff8128c930-ffffffff8128ca4b: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129c560)
Location: mm/mempolicy.c:1645
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff8129c560-ffffffff8129c67b: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d01b0)
Location: mm/mempolicy.c:1714
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff812d01b0-ffffffff812d02cb: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbcd0)
Location: mm/mempolicy.c:1690
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff812dbcd0-ffffffff812dbdeb: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3550)
Location: mm/mempolicy.c:1704
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff812e3550-ffffffff812e365d: __do_compat_sys_mbind (STB_LOCAL)
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
In mm/mempolicy.c (ffff80001033b3e0)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_mbind
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
In mm/mempolicy.c (c000000000416210)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_mbind
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294b40)
Location: mm/mempolicy.c:1645
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff81294b40-ffffffff81294c5b: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81286750)
Location: mm/mempolicy.c:1645
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff81286750-ffffffff8128686b: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292950)
Location: mm/mempolicy.c:1645
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff81292950-ffffffff81292a6b: __do_compat_sys_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t *nmask, compat_ulong_t maxnode, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a2720)
Location: mm/mempolicy.c:1645
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
**Symbols:**

```
ffffffff812a2720-ffffffff812a283b: __do_compat_sys_mbind (STB_LOCAL)
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
