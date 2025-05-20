# Function: <code>copy_from_buffer</code>

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
int copy_from_buffer(void *dst, unsigned int offset, unsigned int size, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b110)
Location: arch/x86/kernel/fpu/xstate.c:1081
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
**Symbols:**

```
ffffffff8104b110-ffffffff8104b187: copy_from_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_from_buffer(void *dst, unsigned int offset, unsigned int size, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810554f0)
Location: arch/x86/kernel/fpu/xstate.c:1186
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
**Symbols:**

```
ffffffff810554f0-ffffffff81055566: copy_from_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_from_buffer(void *dst, unsigned int offset, unsigned int size, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810630f0)
Location: arch/x86/kernel/fpu/xstate.c:1190
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
**Symbols:**

```
ffffffff810630f0-ffffffff81063166: copy_from_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_from_buffer(void *dst, unsigned int offset, unsigned int size, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064a40)
Location: arch/x86/kernel/fpu/xstate.c:1195
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
**Symbols:**

```
ffffffff81064a40-ffffffff81064ab6: copy_from_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_from_buffer(void *dst, unsigned int offset, unsigned int size, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bed0)
Location: arch/x86/kernel/fpu/xstate.c:1194
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
**Symbols:**

```
ffffffff8106bed0-ffffffff8106bf46: copy_from_buffer (STB_LOCAL)
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
