# Function: <code>sigprocmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090ba0)
Location: kernel/signal.c:2501
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
```
**Symbols:**

```
ffffffff81090ba0-ffffffff81090c34: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093c50)
Location: kernel/signal.c:2501
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
```
**Symbols:**

```
ffffffff81093c50-ffffffff81093ce4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098c30)
Location: kernel/signal.c:2514
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
```
**Symbols:**

```
ffffffff81098c30-ffffffff81098cc4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095ec0)
Location: kernel/signal.c:2535
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
**Symbols:**

```
ffffffff81095ec0-ffffffff81095f54: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cd10)
Location: kernel/signal.c:2536
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:SyS_rt_sigprocmask
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
**Symbols:**

```
ffffffff8109cd10-ffffffff8109cda4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1530)
Location: kernel/signal.c:2669
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:do_pselect
  - fs/select.c:do_pselect
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
**Symbols:**

```
ffffffff810a1530-ffffffff810a15c4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9ab0)
Location: kernel/signal.c:2768
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810a9ab0-ffffffff810a9b44: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac320)
Location: kernel/signal.c:2927
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810ac320-ffffffff810ac3b4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2930)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810b2930-ffffffff810b29c4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb3c0)
Location: kernel/signal.c:2950
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810bb3c0-ffffffff810bb454: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6680)
Location: kernel/signal.c:2970
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810b6680-ffffffff810b6714: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5960)
Location: kernel/signal.c:2992
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810b5960-ffffffff810b5a3d: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c7f60)
Location: kernel/signal.c:3077
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810c7f60-ffffffff810c803d: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810df200)
Location: kernel/signal.c:3057
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810df200-ffffffff810df2d6: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ff520)
Location: kernel/signal.c:3059
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810ff520-ffffffff810ff5f6: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110b570)
Location: kernel/signal.c:3083
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff8110b570-ffffffff8110b640: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114f20)
Location: kernel/signal.c:3094
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff81114f20-ffffffff81114ff0: sigprocmask (STB_GLOBAL)
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
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010e7d8)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_sigset_deactivate
  - virt/kvm/kvm_main.c:kvm_sigset_activate
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
```
**Symbols:**

```
ffff80001010e7d8-ffff80001010e89c: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036661c)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigprocmask
```
**Symbols:**

```
c036661c-c0366718: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155b50)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_sigprocmask
  - kernel/signal.c:__se_sys_rt_sigprocmask
```
**Symbols:**

```
c000000000155b50-c000000000155c34: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf192)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffe0000cf192-ffffffe0000cf224: sigprocmask (STB_GLOBAL)
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
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810acca0)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810acca0-ffffffff810acd34: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b620)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff8109b620-ffffffff8109b6b4: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac200)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810ac200-ffffffff810ac294: sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t *set, sigset_t *oldset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4370)
Location: kernel/signal.c:2932
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
**Symbols:**

```
ffffffff810b4370-ffffffff810b4404: sigprocmask (STB_GLOBAL)
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
