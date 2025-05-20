# Function: <code>__do_sys_madvise</code>

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
In mm/madvise.c (ffffffff81244fab)
Location: mm/madvise.c:801
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/madvise.c (ffffffff812595fa)
Location: mm/madvise.c:802
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:803
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81274c80-ffffffff8127557e: __do_sys_madvise (STB_LOCAL)
ffffffff81275d9e-ffffffff81275e1c: __do_sys_madvise.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1053
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81283a80-ffffffff8128454c: __do_sys_madvise (STB_LOCAL)
ffffffff8128584c-ffffffff812858cf: __do_sys_madvise.cold (STB_LOCAL)
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
In mm/madvise.c (ffffffff812b66e9)
Location: mm/madvise.c:1169
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/madvise.c (ffffffff812c18d9)
Location: mm/madvise.c:1156
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/madvise.c (ffffffff812c87e4)
Location: mm/madvise.c:1157
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130d7b4)
Location: mm/madvise.c:1226
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81378c55)
Location: mm/madvise.c:1421
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f65a5)
Location: mm/madvise.c:1455
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff814294c5)
Location: mm/madvise.c:1458
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81462cf5)
Location: mm/madvise.c:1452
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/madvise.c (ffff80001031dfd8)
Location: mm/madvise.c:1053
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
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
In mm/madvise.c (c0537cfc)
Location: mm/madvise.c:1053
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
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
In mm/madvise.c (c0000000003f2040)
Location: mm/madvise.c:1053
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
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
In mm/madvise.c (ffffffe000221004)
Location: mm/madvise.c:1053
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1053
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff8127c0d0-ffffffff8127cb9c: __do_sys_madvise (STB_LOCAL)
ffffffff8127de9c-ffffffff8127df1f: __do_sys_madvise.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1053
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff8126df80-ffffffff8126ea4c: __do_sys_madvise (STB_LOCAL)
ffffffff8126fcc0-ffffffff8126fd43: __do_sys_madvise.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1053
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81279e70-ffffffff8127a93c: __do_sys_madvise (STB_LOCAL)
ffffffff8127bc3c-ffffffff8127bcbf: __do_sys_madvise.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1053
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81289a50-ffffffff8128a51c: __do_sys_madvise (STB_LOCAL)
ffffffff8128b810-ffffffff8128b893: __do_sys_madvise.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
