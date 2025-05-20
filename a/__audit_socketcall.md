# Function: <code>__audit_socketcall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81129270)
Location: kernel/auditsc.c:2167
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81129270-ffffffff8112930a: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81131430)
Location: kernel/auditsc.c:2171
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81131430-ffffffff811314c6: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b1b0)
Location: kernel/auditsc.c:2179
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff8113b1b0-ffffffff8113b246: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c7d0)
Location: kernel/auditsc.c:2188
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8113c7d0-ffffffff8113c866: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149550)
Location: kernel/auditsc.c:2211
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81149550-ffffffff811495e6: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157ec0)
Location: kernel/auditsc.c:2218
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81157ec0-ffffffff81157f14: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164ec0)
Location: kernel/auditsc.c:2203
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81164ec0-ffffffff81164f14: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811719c0)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff811719c0-ffffffff81171a1a: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d840)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8117d840-ffffffff8117d8d0: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190b00)
Location: kernel/auditsc.c:2371
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81190b00-ffffffff81190b90: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118dd20)
Location: kernel/auditsc.c:2388
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8118dd20-ffffffff8118ddb0: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118ec90)
Location: kernel/auditsc.c:2385
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8118ec90-ffffffff8118ed20: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b7aa0)
Location: kernel/auditsc.c:2399
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff811b7aa0-ffffffff811b7b30: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea910)
Location: kernel/auditsc.c:2671
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff811ea910-ffffffff811ea9be: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81230bd0)
Location: kernel/auditsc.c:2649
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81230bd0-ffffffff81230c7e: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247770)
Location: kernel/auditsc.c:2648
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81247770-ffffffff8124781e: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261550)
Location: kernel/auditsc.c:2638
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81261550-ffffffff812615fe: __audit_socketcall (STB_GLOBAL)
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
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2730)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff8000101f2730-ffff8000101f2798: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432c14)
Location: kernel/auditsc.c:2319
Inline: False
```
**Symbols:**

```
c0432c14-c0432c84: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266f10)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000266f10-c000000000266f88: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165dae)
Location: kernel/auditsc.c:2319
Inline: False
```
**Symbols:**

```
ffffffe000165dae-ffffffe000165e0a: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175e60)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81175e60-ffffffff81175ef0: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81169000)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81169000-ffffffff81169090: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173c30)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81173c30-ffffffff81173cc0: __audit_socketcall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811814f0)
Location: kernel/auditsc.c:2319
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff811814f0-ffffffff81181580: __audit_socketcall (STB_GLOBAL)
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
