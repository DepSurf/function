# Function: <code>uprobe_init_insn</code>

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
In arch/x86/kernel/uprobes.c (ffffffff81065936)
Location: arch/x86/kernel/uprobes.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810656a8)
Location: arch/x86/kernel/uprobes.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81068bd8)
Location: arch/x86/kernel/uprobes.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81067eb8)
Location: arch/x86/kernel/uprobes.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8106c158)
Location: arch/x86/kernel/uprobes.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8106ef8f)
Location: arch/x86/kernel/uprobes.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81074fff)
Location: arch/x86/kernel/uprobes.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81078bfd)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81079c4d)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_init_insn(struct arch_uprobe *auprobe, struct insn *insn, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810810a0)
Location: arch/x86/kernel/uprobes.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
**Symbols:**

```
ffffffff810810a0-ffffffff81081198: uprobe_init_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_init_insn(struct arch_uprobe *auprobe, struct insn *insn, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080b50)
Location: arch/x86/kernel/uprobes.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
**Symbols:**

```
ffffffff81080b50-ffffffff81080c38: uprobe_init_insn (STB_LOCAL)
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
In arch/x86/kernel/uprobes.c (ffffffff8108196a)
Location: arch/x86/kernel/uprobes.c:277
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81090986)
Location: arch/x86/kernel/uprobes.c:277
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff810a19d6)
Location: arch/x86/kernel/uprobes.c:277
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uprobe_init_insn(struct arch_uprobe *auprobe, struct insn *insn, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810b94c0)
Location: arch/x86/kernel/uprobes.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
**Symbols:**

```
ffffffff810b94c0-ffffffff810b95bc: uprobe_init_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uprobe_init_insn(struct arch_uprobe *auprobe, struct insn *insn, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810bc7a0)
Location: arch/x86/kernel/uprobes.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
**Symbols:**

```
ffffffff810bc7a0-ffffffff810bc89c: uprobe_init_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uprobe_init_insn(struct arch_uprobe *auprobe, struct insn *insn, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810c3920)
Location: arch/x86/kernel/uprobes.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
**Symbols:**

```
ffffffff810c3920-ffffffff810c3a1c: uprobe_init_insn (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81078c4d)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810683fd)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81078bfd)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8107acfd)
Location: arch/x86/kernel/uprobes.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
