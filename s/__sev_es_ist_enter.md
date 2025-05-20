# Function: <code>__sev_es_ist_enter</code>

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
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81c38210)
Location: arch/x86/kernel/sev-es.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c38210-ffffffff81c3828b: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81c2a6d0)
Location: arch/x86/kernel/sev.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c2a6d0-ffffffff81c2a74d: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81d48cc0)
Location: arch/x86/kernel/sev.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81d48cc0-ffffffff81d48d3d: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81f17fe0)
Location: arch/x86/kernel/sev.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81f17fe0-ffffffff81f18096: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff820bf7a0)
Location: arch/x86/kernel/sev.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff820bf7a0-ffffffff820bf856: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff821414a0)
Location: arch/x86/kernel/sev.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff821414a0-ffffffff82141556: __sev_es_ist_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sev_es_ist_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff822233b0)
Location: arch/x86/kernel/sev.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff822233b0-ffffffff82223466: __sev_es_ist_enter (STB_GLOBAL)
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
