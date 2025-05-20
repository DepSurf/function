# Function: <code>delay_mwaitx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff813f6420)
Location: arch/x86/lib/delay.c:92
Inline: False
```
**Symbols:**

```
ffffffff813f6420-ffffffff813f64a5: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8143cff0)
Location: arch/x86/lib/delay.c:92
Inline: False
```
**Symbols:**

```
ffffffff8143cff0-ffffffff8143d075: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81459f70)
Location: arch/x86/lib/delay.c:92
Inline: False
```
**Symbols:**

```
ffffffff81459f70-ffffffff81459ff5: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff818fbe60)
Location: arch/x86/lib/delay.c:92
Inline: True
```
**Symbols:**

```
ffffffff818fbe60-ffffffff818fbef0: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81982cc0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81982cc0-ffffffff81982d50: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff819df1e0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff819df1e0-ffffffff819df26f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1a110)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81a1a110-ffffffff81a1a19f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a89df0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81a89df0-ffffffff81a89e7f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ac10b0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81ac10b0-ffffffff81ac113f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a5ff00)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81a5ff00-ffffffff81a5ff8f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1cfd0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81a1cfd0-ffffffff81a1d05f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81acc2f0)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81acc2f0-ffffffff81acc37f: delay_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void delay_mwaitx(long unsigned int __loops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ad8800)
Location: arch/x86/lib/delay.c:93
Inline: True
```
**Symbols:**

```
ffffffff81ad8800-ffffffff81ad888f: delay_mwaitx (STB_LOCAL)
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
