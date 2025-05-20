# Function: <code>alloc_ldt_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032b10)
Location: arch/x86/kernel/ldt.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:init_new_context
```
**Symbols:**

```
ffffffff81032b10-ffffffff81032b8f: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031ca0)
Location: arch/x86/kernel/ldt.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:init_new_context_ldt
```
**Symbols:**

```
ffffffff81031ca0-ffffffff81031d22: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031930)
Location: arch/x86/kernel/ldt.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:init_new_context_ldt
```
**Symbols:**

```
ffffffff81031930-ffffffff810319af: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8102fb40)
Location: arch/x86/kernel/ldt.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:init_new_context_ldt
```
**Symbols:**

```
ffffffff8102fb40-ffffffff8102fbc1: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031b50)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81031b50-ffffffff81031bd6: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032e10)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81032e10-ffffffff81032e96: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810340d0)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810340d0-ffffffff81034156: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81035f60)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81035f60-ffffffff81035fea: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036780)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036780-ffffffff8103680a: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810385a0)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810385a0-ffffffff8103862a: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038f50)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81038f50-ffffffff81038fda: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103aa40)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8103aa40-ffffffff8103aac6: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040440)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81040440-ffffffff810404cb: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81047d80)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81047d80-ffffffff81047e0c: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81052a50)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81052a50-ffffffff81052adc: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81053a40)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81053a40-ffffffff81053acc: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105ac60)
Location: arch/x86/kernel/ldt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8105ac60-ffffffff8105acec: alloc_ldt_struct (STB_LOCAL)
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
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810368e0)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810368e0-ffffffff8103696a: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026220)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81026220-ffffffff810262aa: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036740)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036740-ffffffff810367ca: alloc_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ldt_struct *alloc_ldt_struct(unsigned int num_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037740)
Location: arch/x86/kernel/ldt.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81037740-ffffffff810377ca: alloc_ldt_struct (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_entries</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
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
