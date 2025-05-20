# Function: <code>kvm_async_pf_task_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063860)
Location: arch/x86/kernel/kvm.c:120
Inline: False
```
**Symbols:**

```
ffffffff81063860-ffffffff81063a91: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810634b0)
Location: arch/x86/kernel/kvm.c:121
Inline: False
```
**Symbols:**

```
ffffffff810634b0-ffffffff810636bd: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066970)
Location: arch/x86/kernel/kvm.c:120
Inline: False
```
**Symbols:**

```
ffffffff81066970-ffffffff81066b79: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81065c70)
Location: arch/x86/kernel/kvm.c:120
Inline: False
```
**Symbols:**

```
ffffffff81065c70-ffffffff81065e82: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a240)
Location: arch/x86/kernel/kvm.c:124
Inline: False
```
**Symbols:**

```
ffffffff8106a240-ffffffff8106a445: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106cec0)
Location: arch/x86/kernel/kvm.c:124
Inline: False
```
**Symbols:**

```
ffffffff8106cec0-ffffffff8106d0af: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81073090)
Location: arch/x86/kernel/kvm.c:115
Inline: False
```
**Symbols:**

```
ffffffff81073090-ffffffff8107327f: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076c20)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81076c20-ffffffff81076e1d: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077c70)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81077c70-ffffffff81077e6d: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076c70)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81076c70-ffffffff81076e6d: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066cd0)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81066cd0-ffffffff81066ebb: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076c20)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81076c20-ffffffff81076e1d: kvm_async_pf_task_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kvm_async_pf_task_wait(u32 token, int interrupt_kernel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078c70)
Location: arch/x86/kernel/kvm.c:102
Inline: False
```
**Symbols:**

```
ffffffff81078c70-ffffffff81078e86: kvm_async_pf_task_wait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int interrupt_kernel</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
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
