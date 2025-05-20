# Function: <code>destroy_context_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032140)
Location: arch/x86/kernel/ldt.c:147
Inline: False
```
**Symbols:**

```
ffffffff81032140-ffffffff8103217a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031dc0)
Location: arch/x86/kernel/ldt.c:147
Inline: False
```
**Symbols:**

```
ffffffff81031dc0-ffffffff81031dfa: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8102ffd0)
Location: arch/x86/kernel/ldt.c:148
Inline: False
```
**Symbols:**

```
ffffffff8102ffd0-ffffffff8103000a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810323d0)
Location: arch/x86/kernel/ldt.c:292
Inline: False
```
**Symbols:**

```
ffffffff810323d0-ffffffff8103240a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810338c0)
Location: arch/x86/kernel/ldt.c:296
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810338c0-ffffffff810338ee: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034c20)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81034c20-ffffffff81034c4e: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036b00)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81036b00-ffffffff81036b3a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037330)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81037330-ffffffff8103736a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810391d0)
Location: arch/x86/kernel/ldt.c:483
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810391d0-ffffffff81039201: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039b00)
Location: arch/x86/kernel/ldt.c:483
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81039b00-ffffffff81039b31: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b5d0)
Location: arch/x86/kernel/ldt.c:489
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff8103b5d0-ffffffff8103b601: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81041030)
Location: arch/x86/kernel/ldt.c:489
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81041030-ffffffff81041061: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81048b50)
Location: arch/x86/kernel/ldt.c:489
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81048b50-ffffffff81048b87: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810538c0)
Location: arch/x86/kernel/ldt.c:489
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810538c0-ffffffff810538f7: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810548a0)
Location: arch/x86/kernel/ldt.c:491
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810548a0-ffffffff810548d7: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105bae0)
Location: arch/x86/kernel/ldt.c:491
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff8105bae0-ffffffff8105bb17: destroy_context_ldt (STB_GLOBAL)
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
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037490)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81037490-ffffffff810374ca: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026e70)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81026e70-ffffffff81026eaa: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810372f0)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810372f0-ffffffff8103732a: destroy_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_context_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810382f0)
Location: arch/x86/kernel/ldt.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810382f0-ffffffff8103832a: destroy_context_ldt (STB_GLOBAL)
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
