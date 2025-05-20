# Function: <code>__do_sys_mq_getsetattr</code>

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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e13c0)
Location: ipc/mqueue.c:1344
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff813e13c0-ffffffff813e1470: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fbfa0)
Location: ipc/mqueue.c:1344
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff813fbfa0-ffffffff813fc049: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81428270)
Location: ipc/mqueue.c:1399
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81428270-ffffffff8142831b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81441fa0)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81441fa0-ffffffff8144204b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81492b80)
Location: ipc/mqueue.c:1480
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81492b80-ffffffff81492c2b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b0480)
Location: ipc/mqueue.c:1480
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff814b0480-ffffffff814b052b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b62d0)
Location: ipc/mqueue.c:1483
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff814b62d0-ffffffff814b637b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150ec10)
Location: ipc/mqueue.c:1485
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8150ec10-ffffffff8150ecbb: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a0010)
Location: ipc/mqueue.c:1497
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff815a0010-ffffffff815a00e2: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816498f0)
Location: ipc/mqueue.c:1496
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff816498f0-ffffffff816499c2: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81681e50)
Location: ipc/mqueue.c:1496
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81681e50-ffffffff81681f22: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816be250)
Location: ipc/mqueue.c:1496
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff816be250-ffffffff816be322: __do_sys_mq_getsetattr (STB_LOCAL)
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052aa50)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_sys_mq_getsetattr
```
**Symbols:**

```
ffff80001052aa50-ffff80001052ac44: __do_sys_mq_getsetattr (STB_LOCAL)
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
In ipc/mqueue.c (c06e4e3c)
Location: ipc/mqueue.c:1394
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000675760)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
**Symbols:**

```
c000000000675760-c000000000675850: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038cdde)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
**Symbols:**

```
ffffffe00038cdde-ffffffe00038d018: __do_sys_mq_getsetattr (STB_LOCAL)
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143a580)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8143a580-ffffffff8143a62b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142aff0)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8142aff0-ffffffff8142b09b: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81436720)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff81436720-ffffffff814367cb: __do_sys_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144cee0)
Location: ipc/mqueue.c:1394
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_getsetattr
  - ipc/mqueue.c:__x64_sys_mq_getsetattr
```
**Symbols:**

```
ffffffff8144cee0-ffffffff8144cf8b: __do_sys_mq_getsetattr (STB_LOCAL)
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
