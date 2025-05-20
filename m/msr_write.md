# Function: <code>msr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8141bab0)
Location: arch/x86/lib/msr.c:53
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
```
**Symbols:**

```
ffffffff8141bab0-ffffffff8141bacd: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81464133)
Location: arch/x86/lib/msr.c:56
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81464000-ffffffff8146401d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814833d3)
Location: arch/x86/lib/msr.c:56
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff814832a0-ffffffff814832bd: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148cb13)
Location: arch/x86/lib/msr.c:56
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8148c9e0-ffffffff8148c9fd: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8ad0)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff814c8ad0-ffffffff814c8aed: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9a60)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff814f9a60-ffffffff814f9a7d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150e300)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8150e300-ffffffff8150e31d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c970)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8153c970-ffffffff8153c98d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d780)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8155d780-ffffffff8155d79d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e72f7)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff815e7200-ffffffff815e721d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c507)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8160c410-ffffffff8160c42d: msr_write (STB_GLOBAL)
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
In arch/x86/lib/msr.c (ffffffff815ef7a7)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
In arch/x86/lib/msr.c (ffffffff8165c8b7)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
In arch/x86/lib/msr.c (ffffffff81775aab)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
In arch/x86/lib/msr.c (ffffffff818a678b)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
In arch/x86/lib/msr.c (ffffffff818e95fb)
Location: arch/x86/lib/msr.c:59
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
In arch/x86/lib/msr.c (ffffffff81930a9b)
Location: arch/x86/lib/msr.c:59
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555d70)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81555d70-ffffffff81555d8d: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8154628d)
Location: arch/x86/lib/msr.c:57
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81546070-ffffffff815460fd: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551ab0)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff81551ab0-ffffffff81551acd: msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msr_write(u32 msr, struct msr *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b940)
Location: arch/x86/lib/msr.c:57
Inline: False
Direct callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
**Symbols:**

```
ffffffff8156b940-ffffffff8156b95d: msr_write (STB_GLOBAL)
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
