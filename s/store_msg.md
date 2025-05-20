# Function: <code>store_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81325510)
Location: ipc/msgutil.c:152
Inline: False
Direct callers:
  - ipc/compat.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff81325510-ffffffff813255a9: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8135a0e0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/compat.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff8135a0e0-ffffffff8135a19e: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813705c0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/compat.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff813705c0-ffffffff8137067e: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81383990)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/compat.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81383990-ffffffff81383a50: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813a7e00)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff813a7e00-ffffffff813a7ec0: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813d7200)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff813d7200-ffffffff813d72c0: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813f1810)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff813f1810-ffffffff813f18d0: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8141dad0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff8141dad0-ffffffff8141db90: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81437920)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81437920-ffffffff814379e0: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81487b50)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81487b50-ffffffff81487c10: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814a5170)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff814a5170-ffffffff814a5230: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814ab110)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff814ab110-ffffffff814ab1c7: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff815035d0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff815035d0-ffffffff81503687: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81594c80)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81594c80-ffffffff81594d4c: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8163d950)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff8163d950-ffffffff8163da1c: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81675e50)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81675e50-ffffffff81675f1c: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff816b2210)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff816b2210-ffffffff816b22dc: store_msg (STB_GLOBAL)
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
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffff80001051e4a8)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffff80001051e4a8-ffff80001051e584: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (c06da514)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
c06da514-c06da670: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (c0000000006675f0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
c0000000006675f0-c00000000066774c: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffe0003857de)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:__se_sys_mq_timedreceive
```
**Symbols:**

```
ffffffe0003857de-ffffffe000385892: store_msg (STB_GLOBAL)
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
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8142ff00)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff8142ff00-ffffffff8142ffc0: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81420980)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81420980-ffffffff81420a40: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8142c0a0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff8142c0a0-ffffffff8142c160: store_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int store_msg(void *dest, struct msg_msg *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814430c0)
Location: ipc/msgutil.c:150
Inline: False
Direct callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff814430c0-ffffffff81443180: store_msg (STB_GLOBAL)
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
