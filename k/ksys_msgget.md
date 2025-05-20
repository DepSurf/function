# Function: <code>ksys_msgget</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7504)
Location: ipc/msg.c:275
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813d8d40-ffffffff813d8da8: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f1b14)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f3360-ffffffff813f33c8: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141de00)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8141fb60-ffffffff8141fbc9: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81437c50)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81439980-ffffffff814399e9: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814882ce)
Location: ipc/msg.c:295
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81489ad0-ffffffff81489b39: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a58ee)
Location: ipc/msg.c:295
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814a7100-ffffffff814a7169: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ab8be)
Location: ipc/msg.c:297
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ad040-ffffffff814ad0a9: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81503d7e)
Location: ipc/msg.c:297
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81505530-ffffffff81505599: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81595ff2)
Location: ipc/msg.c:297
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81596f00-ffffffff81596f7b: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163ef02)
Location: ipc/msg.c:298
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8163fe80-ffffffff8163fefb: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81677432)
Location: ipc/msg.c:298
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816783a0-ffffffff8167841b: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b37f2)
Location: ipc/msg.c:298
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b4760-ffffffff816b47db: ksys_msgget (STB_GLOBAL)
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
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051e7b4)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_sys_msgget
```
**Symbols:**

```
ffff800010520e20-ffff800010520e9c: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06dc17c)
Location: ipc/msg.c:276
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgget
```
**Symbols:**

```
c06dc17c-c06dc200: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000667a88)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__se_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c00000000066a3a0-c00000000066a420: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe000386e26)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__se_sys_msgget
```
**Symbols:**

```
ffffffe000386dc0-ffffffe000386e0c: ksys_msgget (STB_GLOBAL)
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
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81430230)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431f60-ffffffff81431fc9: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81420cb0)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814229e0-ffffffff81422a49: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142c3d0)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8142e100-ffffffff8142e169: ksys_msgget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgget(key_t key, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814433d0)
Location: ipc/msg.c:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81445140-ffffffff814451a9: ksys_msgget (STB_GLOBAL)
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
