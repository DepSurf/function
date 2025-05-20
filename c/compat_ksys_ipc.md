# Function: <code>compat_ksys_ipc</code>

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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81426830)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81426830-ffffffff81426a86: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81440570)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81440570-ffffffff814407c6: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81491330)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81491330-ffffffff81491586: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff814aeb70)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff814aeb70-ffffffff814aedc8: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff814b4990)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff814b4990-ffffffff814b4bfa: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff8150d040)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x64_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff8150d040-ffffffff8150d2aa: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff8159ef70)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff8159ef70-ffffffff8159f1f5: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff816486e0)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff816486e0-ffffffff81648965: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81680c50)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81680c50-ffffffff81680ec0: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff816bd070)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff816bd070-ffffffff816bd2e0: compat_ksys_ipc (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (c000000000673dd0)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__se_compat_sys_ipc
```
**Symbols:**

```
c000000000673dd0-c000000000674240: compat_ksys_ipc (STB_GLOBAL)
```
</details>
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81438b50)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81438b50-ffffffff81438da6: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff814295c0)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff814295c0-ffffffff81429816: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff81434cf0)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff81434cf0-ffffffff81434f46: compat_ksys_ipc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/syscall.c (ffffffff8144be30)
Location: ipc/syscall.c:130
Inline: False
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff8144be30-ffffffff8144c086: compat_ksys_ipc (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
