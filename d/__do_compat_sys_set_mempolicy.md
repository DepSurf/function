# Function: <code>__do_compat_sys_set_mempolicy</code>

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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ad70)
Location: mm/mempolicy.c:1536
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8125ad70-ffffffff8125ae50: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f530)
Location: mm/mempolicy.c:1576
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8126f530-ffffffff8126f60a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ab10)
Location: mm/mempolicy.c:1622
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8128ab10-ffffffff8128abea: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a680)
Location: mm/mempolicy.c:1624
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8129a680-ffffffff8129a75a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cdc20)
Location: mm/mempolicy.c:1693
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812cdc20-ffffffff812cdcfa: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8b60)
Location: mm/mempolicy.c:1669
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812d8b60-ffffffff812d8c3a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0240)
Location: mm/mempolicy.c:1683
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812e0240-ffffffff812e0310: __do_compat_sys_set_mempolicy (STB_LOCAL)
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
In mm/mempolicy.c (ffff800010339120)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
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
In mm/mempolicy.c (c000000000413a70)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_set_mempolicy
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292c60)
Location: mm/mempolicy.c:1624
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81292c60-ffffffff81292d3a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284870)
Location: mm/mempolicy.c:1624
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81284870-ffffffff8128494a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290a70)
Location: mm/mempolicy.c:1624
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81290a70-ffffffff81290b4a: __do_compat_sys_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t *nmask, compat_ulong_t maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a08a0)
Location: mm/mempolicy.c:1624
Inline: False
Direct callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812a08a0-ffffffff812a097a: __do_compat_sys_set_mempolicy (STB_LOCAL)
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
