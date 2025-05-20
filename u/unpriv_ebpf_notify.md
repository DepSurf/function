# Function: <code>unpriv_ebpf_notify</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unpriv_ebpf_notify(int new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810c2420)
Location: arch/x86/kernel/cpu/bugs.c:659
Inline: False
Direct callers:
  - kernel/sysctl.c:bpf_unpriv_handler
```
**Symbols:**

```
ffffffff81c9ac43-ffffffff81c9ac65: unpriv_ebpf_notify.cold (STB_LOCAL)
ffffffff810547b0-ffffffff810547db: unpriv_ebpf_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unpriv_ebpf_notify(int new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81277e10)
Location: arch/x86/kernel/cpu/bugs.c:984
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_unpriv_handler
```
**Symbols:**

```
ffffffff81e4a0e5-ffffffff81e4a107: unpriv_ebpf_notify.cold (STB_LOCAL)
ffffffff81060470-ffffffff810604ab: unpriv_ebpf_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unpriv_ebpf_notify(int new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ebf0)
Location: arch/x86/kernel/cpu/bugs.c:1021
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_unpriv_handler
```
**Symbols:**

```
ffffffff8106ebf0-ffffffff8106ec4e: unpriv_ebpf_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unpriv_ebpf_notify(int new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810704b0)
Location: arch/x86/kernel/cpu/bugs.c:1133
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_unpriv_handler
```
**Symbols:**

```
ffffffff810704b0-ffffffff81070504: unpriv_ebpf_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unpriv_ebpf_notify(int new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077d90)
Location: arch/x86/kernel/cpu/bugs.c:1198
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_unpriv_handler
```
**Symbols:**

```
ffffffff81077d90-ffffffff81077de4: unpriv_ebpf_notify (STB_GLOBAL)
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
