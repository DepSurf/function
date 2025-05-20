# Function: <code>emit_bpf_dispatcher</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:1713
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810a2540-ffffffff810a2784: emit_bpf_dispatcher (STB_LOCAL)
ffffffff810a3295-ffffffff810a32c8: emit_bpf_dispatcher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:1905
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff8109c070-ffffffff8109c2b4: emit_bpf_dispatcher (STB_LOCAL)
ffffffff81bdaeb3-ffffffff81bdaee6: emit_bpf_dispatcher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2116
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff8109c8f0-ffffffff8109cb22: emit_bpf_dispatcher (STB_LOCAL)
ffffffff81bccf46-ffffffff81bccf79: emit_bpf_dispatcher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2182
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810ac0f0-ffffffff810ac322: emit_bpf_dispatcher (STB_LOCAL)
ffffffff81ca3501-ffffffff81ca3534: emit_bpf_dispatcher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2219
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810c20b0-ffffffff810c22ff: emit_bpf_dispatcher (STB_LOCAL)
ffffffff81e52ca6-ffffffff81e52cbc: emit_bpf_dispatcher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs, u8 *image, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810dea70)
Location: arch/x86/net/bpf_jit_comp.c:2339
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810dea70-ffffffff810dece7: emit_bpf_dispatcher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs, u8 *image, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ea070)
Location: arch/x86/net/bpf_jit_comp.c:2342
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810ea070-ffffffff810ea2d6: emit_bpf_dispatcher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int emit_bpf_dispatcher(u8 **pprog, int a, int b, s64 *progs, u8 *image, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2c10)
Location: arch/x86/net/bpf_jit_comp.c:2844
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
```
**Symbols:**

```
ffffffff810f2c10-ffffffff810f2e76: emit_bpf_dispatcher (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *image</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
