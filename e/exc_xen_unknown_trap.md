# Function: <code>exc_xen_unknown_trap</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81c3502b)
Location: arch/x86/xen/enlighten_pv.c:586
Inline: False
```
**Symbols:**

```
ffffffff81c3502b-ffffffff81c3503d: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81c274ab)
Location: arch/x86/xen/enlighten_pv.c:592
Inline: False
```
**Symbols:**

```
ffffffff81c274ab-ffffffff81c274bd: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81d454fb)
Location: arch/x86/xen/enlighten_pv.c:563
Inline: False
```
**Symbols:**

```
ffffffff81d454fb-ffffffff81d4550d: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81f13527)
Location: arch/x86/xen/enlighten_pv.c:566
Inline: False
```
**Symbols:**

```
ffffffff81f13527-ffffffff81f13539: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff820ba610)
Location: arch/x86/xen/enlighten_pv.c:577
Inline: False
```
**Symbols:**

```
ffffffff820ba610-ffffffff820ba622: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82139ec0)
Location: arch/x86/xen/enlighten_pv.c:632
Inline: False
```
**Symbols:**

```
ffffffff82139ec0-ffffffff82139ed2: exc_xen_unknown_trap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_xen_unknown_trap(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8221be30)
Location: arch/x86/xen/enlighten_pv.c:658
Inline: False
```
**Symbols:**

```
ffffffff8221be30-ffffffff8221be42: exc_xen_unknown_trap (STB_GLOBAL)
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
