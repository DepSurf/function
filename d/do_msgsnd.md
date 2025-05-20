# Function: <code>do_msgsnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81326170)
Location: ipc/msg.c:609
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/msg.c:SyS_msgsnd
```
**Symbols:**

```
ffffffff81326170-ffffffff81326546: do_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8135ad80)
Location: ipc/msg.c:609
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgsnd
```
**Symbols:**

```
ffffffff8135ad80-ffffffff8135b19b: do_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81371380)
Location: ipc/msg.c:630
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgsnd
```
**Symbols:**

```
ffffffff81371380-ffffffff813717c0: do_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81384730)
Location: ipc/msg.c:630
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgsnd
```
**Symbols:**

```
ffffffff81384730-ffffffff81384b6b: do_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8a30)
Location: ipc/msg.c:734
Inline: False
Direct callers:
  - ipc/msg.c:compat_SyS_msgsnd
  - ipc/msg.c:SyS_msgsnd
```
**Symbols:**

```
ffffffff813a8a30-ffffffff813a8e93: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7f50)
Location: ipc/msg.c:781
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff813d7f50-ffffffff813d83c1: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f2bc0)
Location: ipc/msg.c:791
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff813f2bc0-ffffffff813f303a: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141e6f0)
Location: ipc/msg.c:816
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8141e6f0-ffffffff8141eb9a: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438540)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81438540-ffffffff814389ea: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488770)
Location: ipc/msg.c:840
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81488770-ffffffff81488c87: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a5da0)
Location: ipc/msg.c:840
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814a5da0-ffffffff814a62bd: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814abd70)
Location: ipc/msg.c:842
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814abd70-ffffffff814ac249: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:842
Inline: False
Direct callers:
  - ipc/msg.c:__x64_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81504240-ffffffff8150472c: do_msgsnd (STB_LOCAL)
ffffffff81cd29a7-ffffffff81cd29dd: do_msgsnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:842
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff815960c0-ffffffff815965eb: do_msgsnd (STB_LOCAL)
ffffffff81e85afd-ffffffff81e85b37: do_msgsnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:848
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8163ef60-ffffffff8163f4ad: do_msgsnd (STB_LOCAL)
ffffffff82072d0b-ffffffff82072d35: do_msgsnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:848
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81677490-ffffffff816779dd: do_msgsnd (STB_LOCAL)
ffffffff820f2962-ffffffff820f298c: do_msgsnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:848
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff816b3850-ffffffff816b3d9d: do_msgsnd (STB_LOCAL)
ffffffff821cfc12-ffffffff821cfc3c: do_msgsnd.cold (STB_LOCAL)
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
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051f1f0)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
```
**Symbols:**

```
ffff80001051f1f0-ffff80001051f668: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06db7c4)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:ksys_msgsnd
```
**Symbols:**

```
c06db7c4-c06dbc30: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000668ae0)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
```
**Symbols:**

```
c000000000668ae0-c0000000006690a8: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe00038607e)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:ksys_msgsnd
```
**Symbols:**

```
ffffffe00038607e-ffffffe00038640c: do_msgsnd (STB_LOCAL)
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
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81430b20)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81430b20-ffffffff81430fca: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814215a0)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814215a0-ffffffff81421a4a: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142ccc0)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8142ccc0-ffffffff8142d16a: do_msgsnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void *mtext, size_t msgsz, int msgflg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444b50)
Location: ipc/msg.c:817
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81444b50-ffffffff81445018: do_msgsnd (STB_LOCAL)
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
