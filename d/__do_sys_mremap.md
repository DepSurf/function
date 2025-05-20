# Function: <code>__do_sys_mremap</code>

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
In mm/mremap.c (ffffffff8123b726)
Location: mm/mremap.c:519
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff8124fae6)
Location: mm/mremap.c:577
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff81261e53)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff81270623)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812a0f60)
Location: mm/mremap.c:663
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812a0f60-ffffffff812a13f5: __do_sys_mremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812ac750)
Location: mm/mremap.c:811
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812ac750-ffffffff812acc32: __do_sys_mremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b1a50)
Location: mm/mremap.c:816
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812b1a50-ffffffff812b1f1c: __do_sys_mremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:895
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812f3620-ffffffff812f3b07: __do_sys_mremap (STB_LOCAL)
ffffffff81cbcaf2-ffffffff81cbcb13: __do_sys_mremap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:886
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff813572e0-ffffffff81357908: __do_sys_mremap (STB_LOCAL)
ffffffff81e6e68b-ffffffff81e6e769: __do_sys_mremap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:889
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff813d18b0-ffffffff813d2089: __do_sys_mremap (STB_LOCAL)
ffffffff8206459c-ffffffff82064669: __do_sys_mremap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:908
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff814064a0-ffffffff81406c3d: __do_sys_mremap (STB_LOCAL)
ffffffff820e3c7d-ffffffff820e3da7: __do_sys_mremap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_mremap(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:975
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81432bb0-ffffffff814332e6: __do_sys_mremap (STB_LOCAL)
ffffffff821c0826-ffffffff821c0950: __do_sys_mremap.cold (STB_LOCAL)
```
</details>
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
In mm/mremap.c (ffff8000103068fc)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c05244d8)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d4834)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe000212060)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
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
In mm/mremap.c (ffffffff81268c73)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff8125af63)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff81266a13)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
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
In mm/mremap.c (ffffffff812763b3)
Location: mm/mremap.c:595
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
