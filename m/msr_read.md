# Function: <code>msr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8141ba50)
Location: arch/x86/lib/msr.c:35
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
```
**Symbols:**

```
ffffffff8141ba50-ffffffff8141baa4: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814640e7)
Location: arch/x86/lib/msr.c:38
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81463fa0-ffffffff81463ff4: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81483387)
Location: arch/x86/lib/msr.c:38
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81483240-ffffffff81483294: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148cac7)
Location: arch/x86/lib/msr.c:38
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8148c980-ffffffff8148c9d4: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8a70)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff814c8a70-ffffffff814c8ac4: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9a00)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff814f9a00-ffffffff814f9a54: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150e2a0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8150e2a0-ffffffff8150e2f4: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c910)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8153c910-ffffffff8153c967: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d720)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8155d720-ffffffff8155d777: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e71a0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff815e71a0-ffffffff815e71f6: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c3b0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8160c3b0-ffffffff8160c406: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef310)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff815ef310-ffffffff815ef366: msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c420)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8165c420-ffffffff8165c476: msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff817754b0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff817754b0-ffffffff81775521: msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a60d0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff818a60d0-ffffffff818a6141: msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e8f00)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff818e8f00-ffffffff818e8f71: msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff819303a0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff819303a0-ffffffff81930411: msr_read (STB_LOCAL)
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
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555d10)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81555d10-ffffffff81555d67: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81546265)
Location: arch/x86/lib/msr.c:39
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81545fd0-ffffffff81546068: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551a50)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81551a50-ffffffff81551aa7: msr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msr_read(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b8e0)
Location: arch/x86/lib/msr.c:39
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8156b8e0-ffffffff8156b937: msr_read (STB_GLOBAL)
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
