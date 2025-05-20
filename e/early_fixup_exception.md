# Function: <code>early_fixup_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int early_fixup_exception(long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81f78019)
Location: arch/x86/mm/extable.c:53
Inline: False
```
**Symbols:**

```
ffffffff81f78019-ffffffff81f78053: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81fa0771)
Location: arch/x86/mm/extable.c:129
Inline: False
```
**Symbols:**

```
ffffffff81fa0771-ffffffff81fa07e4: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81fdbce2)
Location: arch/x86/mm/extable.c:129
Inline: False
```
**Symbols:**

```
ffffffff81fdbce2-ffffffff81fdbd55: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff820bccaf)
Location: arch/x86/mm/extable.c:131
Inline: False
```
**Symbols:**

```
ffffffff820bccaf-ffffffff820bcd37: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff826c3898)
Location: arch/x86/mm/extable.c:203
Inline: False
```
**Symbols:**

```
ffffffff826c3898-ffffffff826c3933: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff826edb1d)
Location: arch/x86/mm/extable.c:203
Inline: False
```
**Symbols:**

```
ffffffff826edb1d-ffffffff826edbb8: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828a46af)
Location: arch/x86/mm/extable.c:231
Inline: False
```
**Symbols:**

```
ffffffff828a46af-ffffffff828a4750: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828bcb7a)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828bcb7a-ffffffff828bcc21: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828c3015)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828c3015-ffffffff828c30bc: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff82ce63fb)
Location: arch/x86/mm/extable.c:172
Inline: False
```
**Symbols:**

```
ffffffff82ce63fb-ffffffff82ce64b8: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff82fd3d6c)
Location: arch/x86/mm/extable.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff82fd3d6c-ffffffff82fd3e29: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff831de8ad)
Location: arch/x86/mm/extable.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff831de8ad-ffffffff831de96a: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff832c1c23)
Location: arch/x86/mm/extable.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff832c1c23-ffffffff832c1ce0: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8347433d)
Location: arch/x86/mm/extable.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff8347433d-ffffffff83474424: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff83e9c100)
Location: arch/x86/mm/extable.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff83e9c100-ffffffff83e9c1e2: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff836bfba0)
Location: arch/x86/mm/extable.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff836bfba0-ffffffff836bfc82: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff838f06c0)
Location: arch/x86/mm/extable.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff838f06c0-ffffffff838f07a2: early_fixup_exception (STB_GLOBAL)
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
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828adfeb)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828adfeb-ffffffff828ae092: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828a61ed)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828a61ed-ffffffff828a6284: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828c0eea)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828c0eea-ffffffff828c0f91: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void early_fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff828c4035)
Location: arch/x86/mm/extable.c:233
Inline: False
```
**Symbols:**

```
ffffffff828c4035-ffffffff828c40dc: early_fixup_exception (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *regs</code>
</li>
<li>
<b>Param added. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ip</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
