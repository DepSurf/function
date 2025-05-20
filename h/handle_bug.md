# Function: <code>handle_bug</code>

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
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbcb40)
Location: arch/x86/kernel/traps.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff81bbcb40-ffffffff81bbcbde: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c35130)
Location: arch/x86/kernel/traps.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff81c35130-ffffffff81c351ce: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c275d0)
Location: arch/x86/kernel/traps.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff81c275d0-ffffffff81c27651: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d45620)
Location: arch/x86/kernel/traps.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff81d45620-ffffffff81d456a1: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f13820)
Location: arch/x86/kernel/traps.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff81f13820-ffffffff81f1389a: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820ba9e0)
Location: arch/x86/kernel/traps.c:301
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff820ba9e0-ffffffff820baa63: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213c0f0)
Location: arch/x86/kernel/traps.c:301
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff8213c0f0-ffffffff8213c18d: handle_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool handle_bug(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221e0f0)
Location: arch/x86/kernel/traps.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_invalid_op
```
**Symbols:**

```
ffffffff8221e0f0-ffffffff8221e18d: handle_bug (STB_LOCAL)
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
