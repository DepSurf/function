# Function: <code>audit_get_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a860)
Location: kernel/audit.c:1886
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8112a860-ffffffff8112a903: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134580)
Location: kernel/audit.c:2025
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81134580-ffffffff81134623: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135a30)
Location: kernel/audit.c:2192
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81135a30-ffffffff81135a92: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81142770)
Location: kernel/audit.c:2200
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81142770-ffffffff811427d8: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81151150)
Location: kernel/audit.c:2253
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81151150-ffffffff811511b9: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115de00)
Location: kernel/audit.c:2251
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8115de00-ffffffff8115de6d: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116a130)
Location: kernel/audit.c:2104
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116a130-ffffffff8116a196: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175fd0)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81175fd0-ffffffff81176036: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188550)
Location: kernel/audit.c:2255
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81188550-ffffffff811885e5: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811858a0)
Location: kernel/audit.c:2272
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff811858a0-ffffffff81185935: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186890)
Location: kernel/audit.c:2272
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81186890-ffffffff81186925: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aecc0)
Location: kernel/audit.c:2311
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff811aecc0-ffffffff811aed55: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0f00)
Location: kernel/audit.c:2357
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff811e0f00-ffffffff811e0f97: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226d40)
Location: kernel/audit.c:2355
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81226d40-ffffffff81226dd8: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d360)
Location: kernel/audit.c:2355
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff8123d360-ffffffff8123d3f8: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81257290)
Location: kernel/audit.c:2377
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81257290-ffffffff81257328: audit_get_tty (STB_GLOBAL)
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
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eb018)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffff8000101eb018-ffff8000101eb0d4: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042ac3c)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c042ac3c-c042acbc: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025c5d0)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c00000000025c5d0-c00000000025c658: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f912)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffe00015f912-ffffffe00015f962: audit_get_tty (STB_GLOBAL)
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
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e5f0)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116e5f0-ffffffff8116e656: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161790)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81161790-ffffffff811617f6: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116c3c0)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116c3c0-ffffffff8116c426: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tty_struct *audit_get_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179b80)
Location: kernel/audit.c:2106
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81179b80-ffffffff81179be6: audit_get_tty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
