# Function: <code>restore_fpregs_from_user</code>

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
int restore_fpregs_from_user(void *buf, u64 xrestore, bool fx_only, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a5a0)
Location: arch/x86/kernel/fpu/signal.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8104a5a0-ffffffff8104a7ab: restore_fpregs_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool restore_fpregs_from_user(void *buf, u64 xrestore, bool fx_only, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff810549c0)
Location: arch/x86/kernel/fpu/signal.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff810549c0-ffffffff81054c15: restore_fpregs_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool restore_fpregs_from_user(void *buf, u64 xrestore, bool fx_only, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81062520)
Location: arch/x86/kernel/fpu/signal.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81062520-ffffffff81062764: restore_fpregs_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool restore_fpregs_from_user(void *buf, u64 xrestore, bool fx_only, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81063ff0)
Location: arch/x86/kernel/fpu/signal.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81063ff0-ffffffff81064221: restore_fpregs_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool restore_fpregs_from_user(void *buf, u64 xrestore, bool fx_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b500)
Location: arch/x86/kernel/fpu/signal.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8106b500-ffffffff8106b740: restore_fpregs_from_user (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
</ul>
</details>
</li>
</ul>
