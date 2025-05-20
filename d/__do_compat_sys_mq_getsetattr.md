# Function: <code>__do_compat_sys_mq_getsetattr</code>

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
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e14b0)
Location: ipc/mqueue.c:1437
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff813e14b0-ffffffff813e15f6: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fc090)
Location: ipc/mqueue.c:1437
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff813fc090-ffffffff813fc1cb: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81428360)
Location: ipc/mqueue.c:1492
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81428360-ffffffff8142849d: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81442090)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81442090-ffffffff814421cd: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81492c70)
Location: ipc/mqueue.c:1573
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81492c70-ffffffff81492dad: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b0570)
Location: ipc/mqueue.c:1573
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff814b0570-ffffffff814b06ad: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b63c0)
Location: ipc/mqueue.c:1576
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff814b63c0-ffffffff814b64f9: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150ed00)
Location: ipc/mqueue.c:1578
Inline: False
Direct callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8150ed00-ffffffff8150ee39: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a0d00)
Location: ipc/mqueue.c:1590
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff815a0d00-ffffffff815a0ea9: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164a6d0)
Location: ipc/mqueue.c:1589
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8164a6d0-ffffffff8164a879: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81683120)
Location: ipc/mqueue.c:1589
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81683120-ffffffff816832c9: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816bf520)
Location: ipc/mqueue.c:1589
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff816bf520-ffffffff816bf6c9: __do_compat_sys_mq_getsetattr (STB_LOCAL)
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
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052ac78)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffff80001052ac78-ffff80001052ae88: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000677680)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_compat_sys_mq_getsetattr
```
**Symbols:**

```
c000000000677680-c0000000006777bc: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143a670)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8143a670-ffffffff8143a7ad: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142b0e0)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8142b0e0-ffffffff8142b21d: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81436810)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81436810-ffffffff8143694d: __do_compat_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144e6d0)
Location: ipc/mqueue.c:1487
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__ia32_compat_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8144e6d0-ffffffff8144e80d: __do_compat_sys_mq_getsetattr (STB_LOCAL)
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
