# Function: <code>sys_ni_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810a0e90)
Location: kernel/sys_ni.c:14
Inline: False
```
**Symbols:**

```
ffffffff810a0e90-ffffffff810a0ea2: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810a4570)
Location: kernel/sys_ni.c:14
Inline: False
```
**Symbols:**

```
ffffffff810a4570-ffffffff810a4582: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810aa1d0)
Location: kernel/sys_ni.c:14
Inline: False
```
**Symbols:**

```
ffffffff810aa1d0-ffffffff810aa1e2: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810a6d90)
Location: kernel/sys_ni.c:14
Inline: False
```
**Symbols:**

```
ffffffff810a6d90-ffffffff810a6da2: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810ad500)
Location: kernel/sys_ni.c:15
Inline: False
```
**Symbols:**

```
ffffffff810ad500-ffffffff810ad512: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b4270)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
ffffffff810b4270-ffffffff810b4282: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810bd3c0)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
ffffffff810bd3c0-ffffffff810bd3d2: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c33f0)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
ffffffff810c33f0-ffffffff810c3402: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c9680)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:__x64_sys_ni_syscall
```
**Symbols:**

```
ffffffff810c9680-ffffffff810c9692: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810d1a80)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff810d1a80-ffffffff810d1a92: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cc520)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff810cc520-ffffffff810cc532: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810ce000)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff810ce000-ffffffff810ce012: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810e1240)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff810e1240-ffffffff810e1252: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810fb510)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff810fb510-ffffffff810fb526: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8111e460)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff8111e460-ffffffff8111e476: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8112b6d0)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff8112b6d0-ffffffff8112b6e6: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81135e20)
Location: kernel/sys_ni.c:20
Inline: True
```
**Symbols:**

```
ffffffff81135e20-ffffffff81135e36: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffff8000101294e8)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/arm64/kernel/sys.c:__arm64_sys_ni_syscall
```
**Symbols:**

```
ffff8000101294e8-ffff800010129504: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (c037b7f0)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
c037b7f0-c037b80c: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (c000000000173b70)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
c000000000173b70-c000000000173b80: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffe0000e00d0)
Location: kernel/sys_ni.c:20
Inline: False
```
**Symbols:**

```
ffffffe0000e00d0-ffffffe0000e00ee: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3a00)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:__x64_sys_ni_syscall
```
**Symbols:**

```
ffffffff810c3a00-ffffffff810c3a12: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b2220)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:__x64_sys_ni_syscall
```
**Symbols:**

```
ffffffff810b2220-ffffffff810b2232: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c2f50)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:__x64_sys_ni_syscall
```
**Symbols:**

```
ffffffff810c2f50-ffffffff810c2f62: sys_ni_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int sys_ni_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb390)
Location: kernel/sys_ni.c:20
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:__x64_sys_ni_syscall
```
**Symbols:**

```
ffffffff810cb390-ffffffff810cb3a2: sys_ni_syscall (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
