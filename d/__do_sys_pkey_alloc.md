# Function: <code>__do_sys_pkey_alloc</code>

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
In mm/mprotect.c (ffffffff81239544)
Location: mm/mprotect.c:591
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff8124d174)
Location: mm/mprotect.c:592
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff8125f494)
Location: mm/mprotect.c:593
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff8126dca4)
Location: mm/mprotect.c:623
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff8129e014)
Location: mm/mprotect.c:649
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812a9380)
Location: mm/mprotect.c:662
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff812a9380-ffffffff812a951d: __do_sys_pkey_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812ae810)
Location: mm/mprotect.c:663
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff812ae810-ffffffff812ae9a7: __do_sys_pkey_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:673
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff812effb0-ffffffff812f0177: __do_sys_pkey_alloc (STB_LOCAL)
ffffffff81cbc94a-ffffffff81cbc972: __do_sys_pkey_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:772
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff813534c0-ffffffff81353667: __do_sys_pkey_alloc (STB_LOCAL)
ffffffff81e6e53a-ffffffff81e6e55b: __do_sys_pkey_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:829
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff813cd7c0-ffffffff813cd960: __do_sys_pkey_alloc (STB_LOCAL)
ffffffff820643fa-ffffffff82064463: __do_sys_pkey_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:850
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81402120-ffffffff814022d9: __do_sys_pkey_alloc (STB_LOCAL)
ffffffff820e3ad8-ffffffff820e3b41: __do_sys_pkey_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mprotect.c (0)
Location: mm/mprotect.c:841
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff8142e750-ffffffff8142e909: __do_sys_pkey_alloc (STB_LOCAL)
ffffffff821c0681-ffffffff821c06ea: __do_sys_pkey_alloc.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812662f4)
Location: mm/mprotect.c:623
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff81258744)
Location: mm/mprotect.c:623
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff81264094)
Location: mm/mprotect.c:623
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
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
In mm/mprotect.c (ffffffff81273a54)
Location: mm/mprotect.c:623
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
</details>
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
