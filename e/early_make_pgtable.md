# Function: <code>early_make_pgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f594a8)
Location: arch/x86/kernel/head64.c:54
Inline: False
```
**Symbols:**

```
ffffffff81f594a8-ffffffff81f5964b: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f8143c)
Location: arch/x86/kernel/head64.c:49
Inline: False
```
**Symbols:**

```
ffffffff81f8143c-ffffffff81f815d8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81fbd43c)
Location: arch/x86/kernel/head64.c:50
Inline: False
```
**Symbols:**

```
ffffffff81fbd43c-ffffffff81fbd5d8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8209d428)
Location: arch/x86/kernel/head64.c:154
Inline: False
```
**Symbols:**

```
ffffffff8209d428-ffffffff8209d5d1: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826a354b)
Location: arch/x86/kernel/head64.c:258
Inline: False
```
**Symbols:**

```
ffffffff826a354b-ffffffff826a356e: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826cc52c)
Location: arch/x86/kernel/head64.c:334
Inline: False
```
**Symbols:**

```
ffffffff826cc52c-ffffffff826cc54f: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82882537)
Location: arch/x86/kernel/head64.c:350
Inline: False
```
**Symbols:**

```
ffffffff82882537-ffffffff8288255a: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828994c5)
Location: arch/x86/kernel/head64.c:352
Inline: False
```
**Symbols:**

```
ffffffff828994c5-ffffffff828994e8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289c4c5)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff8289c4c5-ffffffff8289c4e8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82cc259a)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff82cc259a-ffffffff82cc25bd: early_make_pgtable (STB_GLOBAL)
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
In arch/x86/kernel/head64.c (ffffffff82fae539)
Location: arch/x86/kernel/head64.c:392
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff831b8539)
Location: arch/x86/kernel/head64.c:392
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff832985b3)
Location: arch/x86/kernel/head64.c:392
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff834465d8)
Location: arch/x86/kernel/head64.c:401
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff83e5f75f)
Location: arch/x86/kernel/head64.c:401
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff836949af)
Location: arch/x86/kernel/head64.c:401
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
In arch/x86/kernel/head64.c (ffffffff838c489f)
Location: arch/x86/kernel/head64.c:400
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a4c5)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff8288a4c5-ffffffff8288a4e8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82888469)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff82888469-ffffffff8288848c: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d4c5)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff8289d4c5-ffffffff8289d4e8: early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_make_pgtable(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d4c5)
Location: arch/x86/kernel/head64.c:370
Inline: False
```
**Symbols:**

```
ffffffff8289d4c5-ffffffff8289d4e8: early_make_pgtable (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
