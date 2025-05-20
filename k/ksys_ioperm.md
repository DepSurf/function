# Function: <code>ksys_ioperm</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810318e0)
Location: arch/x86/kernel/ioport.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff810318e0-ffffffff81031b06: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81032bf0)
Location: arch/x86/kernel/ioport.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81032bf0-ffffffff81032e16: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81034a00)
Location: arch/x86/kernel/ioport.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81034a00-ffffffff81034c26: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81035250)
Location: arch/x86/kernel/ioport.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81035250-ffffffff8103545f: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810371a0)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff810371a0-ffffffff81037363: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81038260)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81038260-ffffffff81038421: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81039da0)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81039da0-ffffffff81039f61: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103f750)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff8103f750-ffffffff8103f911: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046e80)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81046e80-ffffffff81047052: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81050fe0)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81050fe0-ffffffff810511ad: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81051d10)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81051d10-ffffffff81051f07: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81058f30)
Location: arch/x86/kernel/ioport.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
**Symbols:**

```
ffffffff81058f30-ffffffff81059127: ksys_ioperm (STB_GLOBAL)
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810353b0)
Location: arch/x86/kernel/ioport.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff810353b0-ffffffff810355bf: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81024cf0)
Location: arch/x86/kernel/ioport.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81024cf0-ffffffff81024f1a: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81035210)
Location: arch/x86/kernel/ioport.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81035210-ffffffff8103541f: ksys_ioperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81036150)
Location: arch/x86/kernel/ioport.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_ioperm
  - arch/x86/kernel/ioport.c:__x64_sys_ioperm
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81036150-ffffffff810363fd: ksys_ioperm (STB_GLOBAL)
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
