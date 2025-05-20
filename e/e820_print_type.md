# Function: <code>e820_print_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void e820_print_type(u32 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67702)
Location: arch/x86/kernel/e820.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_print_map
  - arch/x86/kernel/e820.c:e820_remove_range
```
**Symbols:**

```
ffffffff81f67702-ffffffff81f67798: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void e820_print_type(u32 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f5a6)
Location: arch/x86/kernel/e820.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_remove_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_print_map
```
**Symbols:**

```
ffffffff81f8f5a6-ffffffff81f8f63c: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void e820_print_type(u32 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fca994)
Location: arch/x86/kernel/e820.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_remove_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_print_map
```
**Symbols:**

```
ffffffff81fca994-ffffffff81fcaa2a: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab130)
Location: arch/x86/kernel/e820.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff820ab130-ffffffff820ab1cb: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b18d5)
Location: arch/x86/kernel/e820.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff826b18d5-ffffffff826b1970: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826daff3)
Location: arch/x86/kernel/e820.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff826daff3-ffffffff826db08e: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828913da)
Location: arch/x86/kernel/e820.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff828913da-ffffffff82891475: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8922)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff828a8922-ffffffff828a89c0: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ab986)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff828ab986-ffffffff828aba24: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd0cc1)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff82cd0cc1-ffffffff82cd0d7d: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbcb01)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff82fbcb01-ffffffff82fbcbbd: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c7218)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff831c7218-ffffffff831c72d4: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a8110)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff832a8110-ffffffff832a81cc: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83457545)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff83457545-ffffffff8345760b: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e75ce0)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff83e75ce0-ffffffff83e75df4: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff836977c0)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff836977c0-ffffffff836978d8: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c7540)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff838c7540-ffffffff838c7658: e820_print_type (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899998)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff82899998-ffffffff82899a36: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891c56)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff82891c56-ffffffff82891cf4: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac978)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff828ac978-ffffffff828aca16: e820_print_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac996)
Location: arch/x86/kernel/e820.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__print_table
```
**Symbols:**

```
ffffffff828ac996-ffffffff828aca34: e820_print_type (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 type</code> ➡️ <code>enum e820_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
