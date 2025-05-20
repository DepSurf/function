# Function: <code>__do_sys_brk</code>

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
In mm/mmap.c (ffffffff812375ec)
Location: mm/mmap.c:191
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff8124aebd)
Location: mm/mmap.c:191
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff8125d28d)
Location: mm/mmap.c:193
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff8126ba5d)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b860)
Location: mm/mmap.c:190
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff8129b860-ffffffff8129bafd: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6a80)
Location: mm/mmap.c:190
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff812a6a80-ffffffff812a6d3c: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aca30)
Location: mm/mmap.c:196
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff812aca30-ffffffff812acce6: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ee190)
Location: mm/mmap.c:194
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff812ee190-ffffffff812ee435: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351580)
Location: mm/mmap.c:200
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81351580-ffffffff81351827: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813caa40)
Location: mm/mmap.c:170
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff813caa40-ffffffff813cade5: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ff350)
Location: mm/mmap.c:190
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff813ff350-ffffffff813ff768: __do_sys_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_brk(long unsigned int brk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142b870)
Location: mm/mmap.c:178
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff8142b870-ffffffff8142bcab: __do_sys_brk (STB_LOCAL)
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
In mm/mmap.c (ffff8000103031c4)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_brk
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
In mm/mmap.c (c0521830)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
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
In mm/mmap.c (c0000000003cfb14)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
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
In mm/mmap.c (ffffffe00020fdc2)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
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
In mm/mmap.c (ffffffff812640ad)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff812564cd)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff81261e4d)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In mm/mmap.c (ffffffff8127180d)
Location: mm/mmap.c:187
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
