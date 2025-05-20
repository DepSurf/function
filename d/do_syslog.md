# Function: <code>do_syslog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d94a0)
Location: kernel/printk/printk.c:1297
Inline: False
Direct callers:
  - kernel/printk/printk.c:SyS_syslog
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
```
**Symbols:**

```
ffffffff810d94a0-ffffffff810d99cc: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810de640)
Location: kernel/printk/printk.c:1428
Inline: False
Direct callers:
  - kernel/printk/printk.c:SyS_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810de640-ffffffff810deb8b: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4c10)
Location: kernel/printk/printk.c:1380
Inline: False
Direct callers:
  - kernel/printk/printk.c:SyS_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810e4c10-ffffffff810e50ef: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3ed0)
Location: kernel/printk/printk.c:1430
Inline: True
Direct callers:
  - kernel/printk/printk.c:SyS_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810e3ed0-ffffffff810e43d8: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ec170)
Location: kernel/printk/printk.c:1429
Inline: True
Direct callers:
  - kernel/printk/printk.c:SyS_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810ec170-ffffffff810ec67d: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f3d50)
Location: kernel/printk/printk.c:1433
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810f3d50-ffffffff810f424f: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810feec0)
Location: kernel/printk/printk.c:1449
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810feec0-ffffffff810ff752: do_syslog.part.22 (STB_LOCAL)
ffffffff810ff9c0-ffffffff810ff9ff: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81107580)
Location: kernel/printk/printk.c:1493
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81107580-ffffffff81107e9b: do_syslog.part.0 (STB_LOCAL)
ffffffff81108100-ffffffff81108143: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113940)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81113940-ffffffff8111427d: do_syslog.part.0 (STB_LOCAL)
ffffffff811144e0-ffffffff81114523: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111f9ac)
Location: kernel/printk/printk.c:1531
Inline: True
Inline callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff8111f540-ffffffff8111f94c: do_syslog.part.0 (STB_LOCAL)
ffffffff8111ff90-ffffffff8111ffd3: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111a6fc)
Location: kernel/printk/printk.c:1561
Inline: True
Inline callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff8111a250-ffffffff8111a6a0: do_syslog.part.0 (STB_LOCAL)
ffffffff8111aca0-ffffffff8111ace3: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111ac6c)
Location: kernel/printk/printk.c:1633
Inline: True
Inline callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff8111a790-ffffffff8111ac0c: do_syslog.part.0 (STB_LOCAL)
ffffffff8111b240-ffffffff8111b283: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113a26c)
Location: kernel/printk/printk.c:1632
Inline: True
Inline callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81139e80-ffffffff8113a201: do_syslog.part.0 (STB_LOCAL)
ffffffff81cac1d7-ffffffff81cac216: do_syslog.part.0.cold (STB_LOCAL)
ffffffff8113b450-ffffffff8113b493: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1659
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81e5c931-ffffffff81e5c97e: do_syslog.cold (STB_LOCAL)
ffffffff8115e0e0-ffffffff8115e4b8: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1740
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff82058ab9-ffffffff82058b06: do_syslog.cold (STB_LOCAL)
ffffffff81190fd0-ffffffff811913a8: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1709
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff820d735f-ffffffff820d739e: do_syslog.cold (STB_LOCAL)
ffffffff811a28e0-ffffffff811a2ca8: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1705
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff821b24f0-ffffffff821b252f: do_syslog.cold (STB_LOCAL)
ffffffff811b07a0-ffffffff811b0b68: do_syslog (STB_GLOBAL)
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
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010174ff8)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__arm64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffff800010174ff8-ffff8000101754d8: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c71ac)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__se_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
c03c71ac-c03c77d0: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001ce050)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__se_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
c0000000001ce050-c0000000001cec38: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00011045c)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__se_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffe00011045c-ffffffe000110d32: do_syslog (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110bf20)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff8110bf20-ffffffff8110c85d: do_syslog.part.0 (STB_LOCAL)
ffffffff8110cac0-ffffffff8110cb03: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fcd30)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff810fcd30-ffffffff810fd62b: do_syslog.part.0 (STB_LOCAL)
ffffffff810fd890-ffffffff810fd8d3: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81109e10)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81109e10-ffffffff8110a74d: do_syslog.part.0 (STB_LOCAL)
ffffffff8110a9b0-ffffffff8110a9f3: do_syslog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_syslog(int type, char *buf, int len, int source);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114fa0)
Location: kernel/printk/printk.c:1503
Inline: True
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - fs/proc/kmsg.c:kmsg_poll
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_read
  - fs/proc/kmsg.c:kmsg_release
  - fs/proc/kmsg.c:kmsg_open
```
**Symbols:**

```
ffffffff81114fa0-ffffffff811158a3: do_syslog.part.0 (STB_LOCAL)
ffffffff81115dc0-ffffffff81115e03: do_syslog (STB_GLOBAL)
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
