# Function: <code>umwait_update_control_msr</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048320)
Location: arch/x86/kernel/cpu/umwait.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81048320-ffffffff8104833f: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048bf0)
Location: arch/x86/kernel/cpu/umwait.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81048bf0-ffffffff81048c0f: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104cf45)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff8104cef0-ffffffff8104cf0f: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104c3a5)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff8104c350-ffffffff8104c36f: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104dee5)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff8104de90-ffffffff8104deaf: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810556e5)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81055690-ffffffff810556af: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810616c5)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81061640-ffffffff81061678: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810700f5)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81070050-ffffffff81070088: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81071d05)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81071c60-ffffffff81071c98: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81079525)
Location: arch/x86/kernel/cpu/umwait.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81079480-ffffffff810794b8: umwait_update_control_msr (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048d60)
Location: arch/x86/kernel/cpu/umwait.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81048d60-ffffffff81048d7f: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81038375)
Location: arch/x86/kernel/cpu/umwait.c:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81038300-ffffffff8103832e: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048ba0)
Location: arch/x86/kernel/cpu/umwait.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81048ba0-ffffffff81048bbf: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void umwait_update_control_msr(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81049fb0)
Location: arch/x86/kernel/cpu/umwait.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
**Symbols:**

```
ffffffff81049fb0-ffffffff81049fcf: umwait_update_control_msr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
