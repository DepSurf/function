# Function: <code>__unregister_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81168290)
Location: kernel/trace/trace_kprobe.c:474
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff81168290-ffffffff811682cb: __unregister_trace_kprobe.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81175e40)
Location: kernel/trace/trace_kprobe.c:478
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff811758d0-ffffffff8117590b: __unregister_trace_kprobe.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811818d0)
Location: kernel/trace/trace_kprobe.c:493
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff811812c0-ffffffff811812fb: __unregister_trace_kprobe.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811846a0)
Location: kernel/trace/trace_kprobe.c:499
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff81183f40-ffffffff81183f7b: __unregister_trace_kprobe.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81192370)
Location: kernel/trace/trace_kprobe.c:499
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff81191ca0-ffffffff81191cdb: __unregister_trace_kprobe.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a7430)
Location: kernel/trace/trace_kprobe.c:540
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff811a7430-ffffffff811a7475: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b4ac0)
Location: kernel/trace/trace_kprobe.c:460
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff811b4ac0-ffffffff811b4b05: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c3570)
Location: kernel/trace/trace_kprobe.c:422
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
**Symbols:**

```
ffffffff811c3570-ffffffff811c35e2: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cee00)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811cee00-ffffffff811cee72: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb200)
Location: kernel/trace/trace_kprobe.c:518
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811eb200-ffffffff811eb264: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811e9350)
Location: kernel/trace/trace_kprobe.c:520
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811e9350-ffffffff811e93b4: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea1c0)
Location: kernel/trace/trace_kprobe.c:520
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811ea1c0-ffffffff811ea224: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121b000)
Location: kernel/trace/trace_kprobe.c:516
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff8121b000-ffffffff8121b064: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125a230)
Location: kernel/trace/trace_kprobe.c:514
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff8125a230-ffffffff8125a29c: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812aa620)
Location: kernel/trace/trace_kprobe.c:516
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff812aa620-ffffffff812aa68c: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ccdd0)
Location: kernel/trace/trace_kprobe.c:516
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff812ccdd0-ffffffff812cce3c: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ea7c0)
Location: kernel/trace/trace_kprobe.c:516
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff812ea7c0-ffffffff812ea82c: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024f670)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffff80001024f670-ffff80001024f6d4: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0482814)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
c0482814-c0482880: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ecc40)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
c0000000002ecc40-c0000000002ecd34: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
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
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c7420)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811c7420-ffffffff811c7492: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ba200)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811ba200-ffffffff811ba272: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c51f0)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811c51f0-ffffffff811c5262: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d3450)
Location: kernel/trace/trace_kprobe.c:519
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
```
**Symbols:**

```
ffffffff811d3450-ffffffff811d34c2: __unregister_trace_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
