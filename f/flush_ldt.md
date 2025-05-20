# Function: <code>flush_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *current_mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032b90)
Location: arch/x86/kernel/ldt.c:25
Inline: True
```
**Symbols:**

```
ffffffff81032b90-ffffffff81032bc3: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *current_mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031d30)
Location: arch/x86/kernel/ldt.c:25
Inline: True
```
**Symbols:**

```
ffffffff81031d30-ffffffff81031d62: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *current_mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810319b0)
Location: arch/x86/kernel/ldt.c:25
Inline: True
```
**Symbols:**

```
ffffffff810319b0-ffffffff810319e2: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8102fbd0)
Location: arch/x86/kernel/ldt.c:25
Inline: True
```
**Symbols:**

```
ffffffff8102fbd0-ffffffff8102fbfe: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032270)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81032270-ffffffff810322fd: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81033760)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81033760-ffffffff810337ed: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034a30)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81034a30-ffffffff81034abd: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810368e0)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff810368e0-ffffffff81036972: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037110)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81037110-ffffffff810371a2: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039090)
Location: arch/x86/kernel/ldt.c:136
Inline: False
```
**Symbols:**

```
ffffffff81039090-ffffffff810390b3: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810399c0)
Location: arch/x86/kernel/ldt.c:136
Inline: False
```
**Symbols:**

```
ffffffff810399c0-ffffffff810399e3: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b490)
Location: arch/x86/kernel/ldt.c:136
Inline: False
```
**Symbols:**

```
ffffffff8103b490-ffffffff8103b4c0: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040ef0)
Location: arch/x86/kernel/ldt.c:136
Inline: False
```
**Symbols:**

```
ffffffff81040ef0-ffffffff81040f20: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810489a0)
Location: arch/x86/kernel/ldt.c:136
Inline: True
```
**Symbols:**

```
ffffffff810489a0-ffffffff810489d3: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810536e0)
Location: arch/x86/kernel/ldt.c:136
Inline: True
```
**Symbols:**

```
ffffffff810536e0-ffffffff81053713: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810546c0)
Location: arch/x86/kernel/ldt.c:136
Inline: True
```
**Symbols:**

```
ffffffff810546c0-ffffffff810546f3: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105b900)
Location: arch/x86/kernel/ldt.c:136
Inline: True
```
**Symbols:**

```
ffffffff8105b900-ffffffff8105b933: flush_ldt (STB_LOCAL)
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
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037270)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81037270-ffffffff81037302: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026bd0)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81026bd0-ffffffff81026d83: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810370d0)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff810370d0-ffffffff81037162: flush_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_ldt(void *__mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810380d0)
Location: arch/x86/kernel/ldt.c:52
Inline: False
```
**Symbols:**

```
ffffffff810380d0-ffffffff81038162: flush_ldt (STB_LOCAL)
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
<b>Param added. </b>
<code>void *__mm</code>
</li>
<li>
<b>Param removed. </b>
<code>void *current_mm</code>
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
