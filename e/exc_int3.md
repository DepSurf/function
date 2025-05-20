# Function: <code>exc_int3</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbd480)
Location: arch/x86/kernel/traps.c:630
Inline: False
```
**Symbols:**

```
ffffffff81bbd480-ffffffff81bbd5b6: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c35b30)
Location: arch/x86/kernel/traps.c:638
Inline: False
```
**Symbols:**

```
ffffffff81c35b30-ffffffff81c35bfb: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c27fd0)
Location: arch/x86/kernel/traps.c:639
Inline: False
```
**Symbols:**

```
ffffffff81c27fd0-ffffffff81c2809b: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d46140)
Location: arch/x86/kernel/traps.c:674
Inline: False
```
**Symbols:**

```
ffffffff81d46140-ffffffff81d4620b: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f143c0)
Location: arch/x86/kernel/traps.c:810
Inline: False
```
**Symbols:**

```
ffffffff81f143c0-ffffffff81f144a4: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820bb700)
Location: arch/x86/kernel/traps.c:819
Inline: False
```
**Symbols:**

```
ffffffff820bb700-ffffffff820bb7e4: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213ce30)
Location: arch/x86/kernel/traps.c:820
Inline: False
```
**Symbols:**

```
ffffffff8213ce30-ffffffff8213cf14: exc_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_int3(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221ee50)
Location: arch/x86/kernel/traps.c:734
Inline: False
```
**Symbols:**

```
ffffffff8221ee50-ffffffff8221ef34: exc_int3 (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
