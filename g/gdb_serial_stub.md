# Function: <code>gdb_serial_stub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81130fd0)
Location: kernel/debug/gdbstub.c:943
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81130fd0-ffffffff81131c3f: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81139320)
Location: kernel/debug/gdbstub.c:943
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81139320-ffffffff81139faf: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff811430b0)
Location: kernel/debug/gdbstub.c:943
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811430b0-ffffffff81143d41: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81144920)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81144920-ffffffff81145a2a: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff811515b0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811515b0-ffffffff81152336: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81161127-ffffffff8116117b: gdb_serial_stub.cold.18 (STB_LOCAL)
ffffffff811601f0-ffffffff81160ec6: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8116df57-ffffffff8116dfab: gdb_serial_stub.cold.18 (STB_LOCAL)
ffffffff8116cf60-ffffffff8116dcf4: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8117adbb-ffffffff8117add3: gdb_serial_stub.cold (STB_LOCAL)
ffffffff8117a170-ffffffff8117ab80: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81186c4b-ffffffff81186c63: gdb_serial_stub.cold (STB_LOCAL)
ffffffff81186000-ffffffff81186a10: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:957
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8119b10b-ffffffff8119b123: gdb_serial_stub.cold (STB_LOCAL)
ffffffff8119a800-ffffffff8119aec3: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:957
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81be4ce1-ffffffff81be4cf9: gdb_serial_stub.cold (STB_LOCAL)
ffffffff81197990-ffffffff81198033: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:957
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81bd6b55-ffffffff81bd6b6d: gdb_serial_stub.cold (STB_LOCAL)
ffffffff81198520-ffffffff81198e90: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:954
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81cb3b8b-ffffffff81cb3ba3: gdb_serial_stub.cold (STB_LOCAL)
ffffffff811c22e0-ffffffff811c2c56: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:954
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81e64a35-ffffffff81e64a4d: gdb_serial_stub.cold (STB_LOCAL)
ffffffff811f5a40-ffffffff811f642c: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff8123cc40)
Location: kernel/debug/gdbstub.c:954
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8123cc40-ffffffff8123d605: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81253c60)
Location: kernel/debug/gdbstub.c:954
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81253c60-ffffffff8125463d: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff8126dad0)
Location: kernel/debug/gdbstub.c:954
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8126dad0-ffffffff8126e4ad: gdb_serial_stub (STB_GLOBAL)
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
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffff8000101fc048)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffff8000101fc048-ffff8000101fca70: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (c043be18)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
c043be18-c043caa8: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (c0000000002741c0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
c0000000002741c0-c000000000274f90: gdb_serial_stub (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8117f26b-ffffffff8117f283: gdb_serial_stub.cold (STB_LOCAL)
ffffffff8117e620-ffffffff8117f030: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811723bb-ffffffff811723d3: gdb_serial_stub.cold (STB_LOCAL)
ffffffff81171770-ffffffff81172180: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8117d03b-ffffffff8117d053: gdb_serial_stub.cold (STB_LOCAL)
ffffffff8117c3f0-ffffffff8117ce00: gdb_serial_stub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gdb_serial_stub(struct kgdb_state *ks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:944
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8118a95b-ffffffff8118a973: gdb_serial_stub.cold (STB_LOCAL)
ffffffff81189d10-ffffffff8118a720: gdb_serial_stub (STB_GLOBAL)
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
