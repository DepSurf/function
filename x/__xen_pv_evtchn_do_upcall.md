# Function: <code>__xen_pv_evtchn_do_upcall</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81bbc933)
Location: arch/x86/entry/common.c:798
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81004d20-ffffffff81004d3c: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81c34ed4)
Location: arch/x86/entry/common.c:253
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810045e0-ffffffff810045fc: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81c2733f)
Location: arch/x86/entry/common.c:256
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810045d0-ffffffff810045ff: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81d4538f)
Location: arch/x86/entry/common.c:291
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81004c00-ffffffff81004c2f: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81f1331d)
Location: arch/x86/entry/common.c:291
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81003c80-ffffffff81003cb5: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff820ba38d)
Location: arch/x86/entry/common.c:291
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81004580-ffffffff810045b5: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff82139b9d)
Location: arch/x86/entry/common.c:291
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81003d40-ffffffff81003d77: __xen_pv_evtchn_do_upcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __xen_pv_evtchn_do_upcall(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8221bb0d)
Location: arch/x86/entry/common.c:429
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81006650-ffffffff81006687: __xen_pv_evtchn_do_upcall (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *regs</code>
</li>
</ul>
</details>
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
