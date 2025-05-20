# Function: <code>do_sys_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81221e60)
Location: fs/select.c:870
Inline: False
Direct callers:
  - fs/select.c:do_restart_poll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
```
**Symbols:**

```
ffffffff81221e60-ffffffff812223c0: do_sys_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81249b20)
Location: fs/select.c:876
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_poll
  - fs/select.c:do_restart_poll
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
```
**Symbols:**

```
ffffffff81249b20-ffffffff8124a07e: do_sys_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125caf0)
Location: fs/select.c:884
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_poll
  - fs/select.c:do_restart_poll
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_ppoll
```
**Symbols:**

```
ffffffff8125caf0-ffffffff8125d03c: do_sys_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812696b0)
Location: fs/select.c:928
Inline: False
Direct callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812696b0-ffffffff81269c3d: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128bf60)
Location: fs/select.c:925
Inline: False
Direct callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8128bf60-ffffffff8128c4dd: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b2750)
Location: fs/select.c:926
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812b2750-ffffffff812b2c65: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c7860)
Location: fs/select.c:965
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812c7860-ffffffff812c7d81: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e43f0)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812e43f0-ffffffff812e4928: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f5e30)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812f5e30-ffffffff812f6342: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132ef50)
Location: fs/select.c:970
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8132ef50-ffffffff8132f18a: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133a830)
Location: fs/select.c:970
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8133a830-ffffffff8133aa8f: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81340d30)
Location: fs/select.c:970
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff81340d30-ffffffff81340f7a: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138e6f0)
Location: fs/select.c:973
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8138e6f0-ffffffff8138e93a: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140f9b0)
Location: fs/select.c:974
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8140f9b0-ffffffff8140fc3e: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8149a5f0)
Location: fs/select.c:974
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff8149a5f0-ffffffff8149a87e: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cf6a0)
Location: fs/select.c:974
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff814cf6a0-ffffffff814cf929: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81501fe0)
Location: fs/select.c:974
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff81501fe0-ffffffff81502269: do_sys_poll (STB_LOCAL)
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
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a2f40)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__arm64_compat_sys_ppoll_time64
  - fs/select.c:__arm64_compat_sys_ppoll_time32
  - fs/select.c:__arm64_sys_ppoll
  - fs/select.c:__arm64_sys_poll
  - fs/select.c:__arm64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffff8000103a2f40-ffff8000103a3600: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0585830)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll_time32
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:__se_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
c0585830-c0585db0: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049cc90)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__se_compat_sys_ppoll_time64
  - fs/select.c:__se_compat_sys_ppoll_time32
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:__se_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
c00000000049cc90-c00000000049d36c: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026b026)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:__se_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffe00026b026-ffffffe00026b414: do_sys_poll (STB_LOCAL)
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
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ee410)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812ee410-ffffffff812ee922: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812df040)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812df040-ffffffff812df552: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ec220)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812ec220-ffffffff812ec732: do_sys_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd *ufds, unsigned int nfds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fd220)
Location: fs/select.c:960
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
**Symbols:**

```
ffffffff812fd220-ffffffff812fd732: do_sys_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *end_time</code> ➡️ <code>struct timespec64 *end_time</code>
</li>
</ul>
</details>
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
