# Function: <code>__traceiter_nmi_handler</code>

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
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81038870)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff81038870-ffffffff810388c1: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103a390)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff8103a390-ffffffff8103a3df: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103fd40)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff8103fd40-ffffffff8103fd8f: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81047510)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff81047510-ffffffff8104756b: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81051f10)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff81051f10-ffffffff81051f6b: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81052c50)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff81052c50-ffffffff81052cab: __traceiter_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_nmi_handler(void *__data, void *handler, s64 delta_ns, int handled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81059e70)
Location: include/trace/events/nmi.h:11
Inline: False
```
**Symbols:**

```
ffffffff81059e70-ffffffff81059ecb: __traceiter_nmi_handler (STB_GLOBAL)
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
