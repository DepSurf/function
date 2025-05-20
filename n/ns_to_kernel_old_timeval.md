# Function: <code>ns_to_kernel_old_timeval</code>

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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110e10)
Location: kernel/time/time.c:491
Inline: False
```
**Symbols:**

```
ffffffff81110e10-ffffffff81110e8e: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c5e0)
Location: kernel/time/time.c:429
Inline: False
```
**Symbols:**

```
ffffffff8111c5e0-ffffffff8111c657: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126f10)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81126f10-ffffffff81126f8b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132eb0)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81132eb0-ffffffff81132f2b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142430)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81142430-ffffffff811424e2: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e640)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff8113e640-ffffffff8113e6f2: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f890)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff8113f890-ffffffff8113f92d: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162d20)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81162d20-ffffffff81162dbd: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195c70)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81195c70-ffffffff81195d0b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3bd0)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff811d3bd0-ffffffff811d3c6b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7ec0)
Location: kernel/time/time.c:452
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff811e7ec0-ffffffff811e7f5b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdbf0)
Location: kernel/time/time.c:470
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff811fdbf0-ffffffff811fdc8b: ns_to_kernel_old_timeval (STB_GLOBAL)
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a1d0)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffff80001019a1d0-ffff80001019a264: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4ad4)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
c03e4ad4-c03e4b94: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fab60)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
c0000000001fab60-c0000000001fabf4: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a8be)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffe00012a8be-ffffffe00012a90a: ns_to_kernel_old_timeval (STB_GLOBAL)
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b660)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff8112b660-ffffffff8112b6db: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ded0)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff8111ded0-ffffffff8111df4b: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129380)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81129380-ffffffff811293fb: ns_to_kernel_old_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811359d0)
Location: kernel/time/time.c:497
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff811359d0-ffffffff81135a4b: ns_to_kernel_old_timeval (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const s64 nsec</code> ➡️ <code>s64 nsec</code>
</li>
</ul>
</details>
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
