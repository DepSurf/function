# Function: <code>msr_to_offset</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810446ea)
Location: arch/x86/kernel/cpu/mcheck/mce.c:354
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043520)
Location: arch/x86/kernel/cpu/mcheck/mce.c:397
Inline: False
```
**Symbols:**

```
ffffffff81043520-ffffffff81043595: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044f70)
Location: arch/x86/kernel/cpu/mcheck/mce.c:422
Inline: False
```
**Symbols:**

```
ffffffff81044f70-ffffffff81044fe5: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045190)
Location: arch/x86/kernel/cpu/mcheck/mce.c:353
Inline: False
```
**Symbols:**

```
ffffffff81045190-ffffffff8104520d: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048af0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:362
Inline: False
```
**Symbols:**

```
ffffffff81048af0-ffffffff81048b7f: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b410)
Location: arch/x86/kernel/cpu/mcheck/mce.c:359
Inline: False
```
**Symbols:**

```
ffffffff8104b410-ffffffff8104b4a1: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048a80)
Location: arch/x86/kernel/cpu/mce/core.c:357
Inline: False
```
**Symbols:**

```
ffffffff81048a80-ffffffff81048b11: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bb40)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104bb40-ffffffff8104bbd1: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c500)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104c500-ffffffff8104c591: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050e00)
Location: arch/x86/kernel/cpu/mce/core.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_clear_state
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff81050e00-ffffffff81050e91: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ffd0)
Location: arch/x86/kernel/cpu/mce/core.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104ffd0-ffffffff81050061: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051b40)
Location: arch/x86/kernel/cpu/mce/core.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff81051b40-ffffffff81051bd1: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a0d0)
Location: arch/x86/kernel/cpu/mce/core.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8105a0d0-ffffffff8105a161: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066860)
Location: arch/x86/kernel/cpu/mce/core.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_wrmsrl
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff81066860-ffffffff81066906: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81075b50)
Location: arch/x86/kernel/cpu/mce/core.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_wrmsrl
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff81075b50-ffffffff81075c03: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077cd0)
Location: arch/x86/kernel/cpu/mce/core.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_wrmsrl
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff81077cd0-ffffffff81077d83: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f1b0)
Location: arch/x86/kernel/cpu/mce/core.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_wrmsrl
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8107f1b0-ffffffff8107f263: msr_to_offset (STB_LOCAL)
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
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c670)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104c670-ffffffff8104c701: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bad0)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8103bad0-ffffffff8103bb61: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c4b0)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104c4b0-ffffffff8104c541: msr_to_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msr_to_offset(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d8c0)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_rdmsrl
```
**Symbols:**

```
ffffffff8104d8c0-ffffffff8104d951: msr_to_offset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
