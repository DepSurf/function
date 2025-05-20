# Function: <code>do_mq_notify</code>

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
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138c110)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
**Symbols:**

```
ffffffff8138c110-ffffffff8138c560: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b14c0)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
**Symbols:**

```
ffffffff813b14c0-ffffffff813b1910: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e1640)
Location: ipc/mqueue.c:1162
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff813e1640-ffffffff813e1a83: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fc210)
Location: ipc/mqueue.c:1162
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff813fc210-ffffffff813fc653: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81428e60)
Location: ipc/mqueue.c:1217
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff81428e60-ffffffff814292ea: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81442b90)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff81442b90-ffffffff81443019: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81493490)
Location: ipc/mqueue.c:1301
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff81493490-ffffffff8149395d: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b0d90)
Location: ipc/mqueue.c:1301
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff814b0d90-ffffffff814b12b8: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b6c00)
Location: ipc/mqueue.c:1304
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff814b6c00-ffffffff814b7124: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150f540)
Location: ipc/mqueue.c:1306
Inline: False
Direct callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff8150f540-ffffffff8150fa64: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a2810)
Location: ipc/mqueue.c:1318
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff815a2810-ffffffff815a2cb7: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164c330)
Location: ipc/mqueue.c:1317
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff8164c330-ffffffff8164c7d7: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81684a70)
Location: ipc/mqueue.c:1317
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff81684a70-ffffffff81684f33: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816c0eb0)
Location: ipc/mqueue.c:1316
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff816c0eb0-ffffffff816c135d: do_mq_notify (STB_LOCAL)
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
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052bfb0)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_notify
  - ipc/mqueue.c:__arm64_sys_mq_notify
```
**Symbols:**

```
ffff80001052bfb0-ffff80001052c310: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e40a4)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_notify
```
**Symbols:**

```
c06e40a4-c06e44fc: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c0000000006779c0)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_compat_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
```
**Symbols:**

```
c0000000006779c0-c000000000677ea8: do_mq_notify (STB_LOCAL)
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
In ipc/mqueue.c (ffffffe00038e4b0)
Location: ipc/mqueue.c:1216
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
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
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143b170)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff8143b170-ffffffff8143b5f9: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142bbe0)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff8142bbe0-ffffffff8142c069: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81437310)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff81437310-ffffffff81437799: do_mq_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent *notification);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144ea30)
Location: ipc/mqueue.c:1216
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_sys_mq_notify
  - ipc/mqueue.c:__x64_sys_mq_notify
```
**Symbols:**

```
ffffffff8144ea30-ffffffff8144ee99: do_mq_notify (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
