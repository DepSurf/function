# Function: <code>do_mincore</code>

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
In mm/mincore.c (ffffffff811c2a66)
Location: mm/mincore.c:173
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
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
In mm/mincore.c (ffffffff811de5e6)
Location: mm/mincore.c:174
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff811ee406)
Location: mm/mincore.c:175
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff811f93ec)
Location: mm/mincore.c:176
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8121180c)
Location: mm/mincore.c:177
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8123205b)
Location: mm/mincore.c:177
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff8124582b)
Location: mm/mincore.c:177
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff81257920)
Location: mm/mincore.c:201
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff81265e5c)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_mincore(long unsigned int addr, long unsigned int pages, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81296010)
Location: mm/mincore.c:208
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
```
**Symbols:**

```
ffffffff81296010-ffffffff81296113: do_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_mincore(long unsigned int addr, long unsigned int pages, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812a0d50)
Location: mm/mincore.c:184
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
```
**Symbols:**

```
ffffffff812a0d50-ffffffff812a0e53: do_mincore (STB_LOCAL)
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
In mm/mincore.c (ffffffff812a673c)
Location: mm/mincore.c:185
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
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
In mm/mincore.c (ffffffff812e7c04)
Location: mm/mincore.c:185
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
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
In mm/mincore.c (ffffffff81348e7c)
Location: mm/mincore.c:187
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_mincore(long unsigned int addr, long unsigned int pages, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813c1230)
Location: mm/mincore.c:187
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
```
**Symbols:**

```
ffffffff813c1230-ffffffff813c136a: do_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_mincore(long unsigned int addr, long unsigned int pages, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813f5f80)
Location: mm/mincore.c:187
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff813f5f80-ffffffff813f60c0: do_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_mincore(long unsigned int addr, long unsigned int pages, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81421c30)
Location: mm/mincore.c:187
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff81421c30-ffffffff81421d70: do_mincore (STB_LOCAL)
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
In mm/mincore.c (ffff8000102fd1e8)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
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
In mm/mincore.c (c051c7e4)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
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
In mm/mincore.c (c0000000003c8158)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
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
In mm/mincore.c (ffffffe00020bd00)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
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
In mm/mincore.c (ffffffff8125e4ac)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff8125093c)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff8125c24c)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
In mm/mincore.c (ffffffff8126bc3c)
Location: mm/mincore.c:207
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
