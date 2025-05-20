# Function: <code>do_inotify_init</code>

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
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812e6db0)
Location: fs/notify/inotify/inotify_user.c:656
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff812e6db0-ffffffff812e6f12: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812fb990)
Location: fs/notify/inotify/inotify_user.c:664
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff812fb990-ffffffff812fbb05: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8131c2f0)
Location: fs/notify/inotify/inotify_user.c:654
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff8131c2f0-ffffffff8131c463: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8132f0c0)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff8132f0c0-ffffffff8132f233: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813694a5)
Location: fs/notify/inotify/inotify_user.c:663
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81369360-ffffffff813693d7: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376785)
Location: fs/notify/inotify/inotify_user.c:670
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81376640-ffffffff813766b7: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8137ce20)
Location: fs/notify/inotify/inotify_user.c:669
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff8137ce20-ffffffff8137cf8b: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813c9cd0)
Location: fs/notify/inotify/inotify_user.c:674
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff813c9cd0-ffffffff813c9e3b: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814517a0)
Location: fs/notify/inotify/inotify_user.c:695
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff814517a0-ffffffff8145192c: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814e04a0)
Location: fs/notify/inotify/inotify_user.c:695
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff814e04a0-ffffffff814e062c: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81516d50)
Location: fs/notify/inotify/inotify_user.c:695
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81516d50-ffffffff81516edc: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8154b140)
Location: fs/notify/inotify/inotify_user.c:694
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff8154b140-ffffffff8154b2cc: do_inotify_init (STB_LOCAL)
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
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffff8000103ebcc8)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_init1
```
**Symbols:**

```
ffff8000103ebcc8-ffff8000103ebe1c: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c05c2d80)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1
```
**Symbols:**

```
c05c2d80-c05c2ee8: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c0000000004f3690)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1
```
**Symbols:**

```
c0000000004f3690-c0000000004f3848: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffe00029ff12)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1
```
**Symbols:**

```
ffffffe00029ff12-ffffffe0002a0042: do_inotify_init (STB_LOCAL)
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
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813276a0)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff813276a0-ffffffff81327813: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81318240)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81318240-ffffffff813183b3: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81325170)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81325170-ffffffff813252e3: do_inotify_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_inotify_init(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81337510)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1
```
**Symbols:**

```
ffffffff81337510-ffffffff81337683: do_inotify_init (STB_LOCAL)
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
