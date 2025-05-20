# Function: <code>__fpu_restore_sig</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __fpu_restore_sig(void *buf, void *buf_fx, bool ia32_fxstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a7b0)
Location: arch/x86/kernel/fpu/signal.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff8104a7b0-ffffffff8104aaf9: __fpu_restore_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __fpu_restore_sig(void *buf, void *buf_fx, bool ia32_fxstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81054c20)
Location: arch/x86/kernel/fpu/signal.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff81054c20-ffffffff81054fba: __fpu_restore_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __fpu_restore_sig(void *buf, void *buf_fx, bool ia32_fxstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81062780)
Location: arch/x86/kernel/fpu/signal.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff81062780-ffffffff81062b17: __fpu_restore_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __fpu_restore_sig(void *buf, void *buf_fx, bool ia32_fxstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81064240)
Location: arch/x86/kernel/fpu/signal.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff81064240-ffffffff81064559: __fpu_restore_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __fpu_restore_sig(void *buf, void *buf_fx, bool ia32_fxstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b750)
Location: arch/x86/kernel/fpu/signal.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff8106b750-ffffffff8106ba1b: __fpu_restore_sig (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
