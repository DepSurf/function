# Function: <code>do_mq_open</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138cab0)
Location: ipc/mqueue.c:771
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff8138cab0-ffffffff8138ce7f: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b1e60)
Location: ipc/mqueue.c:771
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff813b1e60-ffffffff813b222f: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e0660)
Location: ipc/mqueue.c:744
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff813e0660-ffffffff813e0968: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fae50)
Location: ipc/mqueue.c:744
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff813fae50-ffffffff813fb158: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81427250)
Location: ipc/mqueue.c:799
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81427250-ffffffff81427556: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81440f80)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81440f80-ffffffff81441286: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81491d50)
Location: ipc/mqueue.c:879
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81491d50-ffffffff81492056: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814af3b0)
Location: ipc/mqueue.c:879
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff814af3b0-ffffffff814af6b6: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b51f0)
Location: ipc/mqueue.c:879
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff814b51f0-ffffffff814b54ee: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150d8b0)
Location: ipc/mqueue.c:881
Inline: False
Direct callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff8150d8b0-ffffffff8150dbdc: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a02d0)
Location: ipc/mqueue.c:893
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff815a02d0-ffffffff815a0609: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81649c30)
Location: ipc/mqueue.c:893
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81649c30-ffffffff81649f69: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81682190)
Location: ipc/mqueue.c:893
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81682190-ffffffff816824b9: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816be590)
Location: ipc/mqueue.c:894
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff816be590-ffffffff816be8b9: do_mq_open (STB_LOCAL)
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
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff800010529438)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_open
  - ipc/mqueue.c:__arm64_sys_mq_open
```
**Symbols:**

```
ffff800010529438-ffff8000105296f8: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e4784)
Location: ipc/mqueue.c:798
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000675d20)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_compat_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c000000000675d20-c000000000676134: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038d90e)
Location: ipc/mqueue.c:798
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
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
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81439560)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81439560-ffffffff81439866: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81429fd0)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81429fd0-ffffffff8142a2d6: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81435700)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff81435700-ffffffff81435a06: do_mq_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_mq_open(const char *u_name, int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144d740)
Location: ipc/mqueue.c:798
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_sys_mq_open
  - ipc/mqueue.c:__x64_sys_mq_open
```
**Symbols:**

```
ffffffff8144d740-ffffffff8144da46: do_mq_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
