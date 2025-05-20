# Function: <code>security_task_prctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e8a0)
Location: security/security.c:998
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8133e8a0-ffffffff8133e920: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373eb0)
Location: security/security.c:1022
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81373eb0-ffffffff81373f31: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a7e0)
Location: security/security.c:1043
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8138a7e0-ffffffff8138a861: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fce0)
Location: security/security.c:1755
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8139fce0-ffffffff8139fea2: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5920)
Location: security/security.c:1717
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff813c5920-ffffffff813c5ae7: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f58f0)
Location: security/security.c:1147
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff813f58f0-ffffffff813f5971: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410f20)
Location: security/security.c:1755
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81410f20-ffffffff81410fa1: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e770)
Location: security/security.c:1774
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8143e770-ffffffff8143e7f8: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458160)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81458160-ffffffff814581e1: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaff0)
Location: security/security.c:2009
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff814aaff0-ffffffff814ab071: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c85f0)
Location: security/security.c:2026
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff814c85f0-ffffffff814c8671: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cec30)
Location: security/security.c:2089
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff814cec30-ffffffff814cecb1: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815278f0)
Location: security/security.c:2097
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff815278f0-ffffffff81527971: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc7e0)
Location: security/security.c:2103
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff815bc7e0-ffffffff815bc873: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668880)
Location: security/security.c:2155
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81668880-ffffffff81668aa8: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0ed0)
Location: security/security.c:3574
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff816a0ed0-ffffffff816a1071: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd8a0)
Location: security/security.c:3633
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff816dd8a0-ffffffff816dd933: security_task_prctl (STB_GLOBAL)
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
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543f60)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
```
**Symbols:**

```
ffff800010543f60-ffff800010544018: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9eac)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c06f9eac-c06f9f38: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006988a0)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c0000000006988a0-c000000000698998: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a023c)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
ffffffe0003a023c-ffffffe0003a02b2: security_task_prctl (STB_GLOBAL)
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
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450740)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81450740-ffffffff814507c1: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441190)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81441190-ffffffff81441211: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c7e0)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8144c7e0-ffffffff8144c861: security_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463bb0)
Location: security/security.c:1813
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81463bb0-ffffffff81463c31: security_task_prctl (STB_GLOBAL)
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
