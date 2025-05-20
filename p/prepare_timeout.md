# Function: <code>prepare_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prepare_timeout(const struct timespec *u_abs_timeout, ktime_t *expires, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8132bd20)
Location: ipc/mqueue.c:668
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff8132bd20-ffffffff8132bd99: prepare_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prepare_timeout(const struct timespec *u_abs_timeout, ktime_t *expires, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813609c0)
Location: ipc/mqueue.c:666
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff813609c0-ffffffff81360a38: prepare_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prepare_timeout(const struct timespec *u_abs_timeout, ktime_t *expires, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813771e0)
Location: ipc/mqueue.c:666
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff813771e0-ffffffff81377258: prepare_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prepare_timeout(const struct timespec *u_abs_timeout, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138ad60)
Location: ipc/mqueue.c:670
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8138ad60-ffffffff8138ada8: prepare_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b2934)
Location: ipc/mqueue.c:670
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e29ab)
Location: ipc/mqueue.c:694
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fd3fb)
Location: ipc/mqueue.c:694
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81429a1b)
Location: ipc/mqueue.c:749
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144374b)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8149441b)
Location: ipc/mqueue.c:829
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b1d7b)
Location: ipc/mqueue.c:829
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b7bfc)
Location: ipc/mqueue.c:829
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8151040c)
Location: ipc/mqueue.c:831
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a251a)
Location: ipc/mqueue.c:843
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164bffa)
Location: ipc/mqueue.c:843
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8168473a)
Location: ipc/mqueue.c:843
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816c0b7a)
Location: ipc/mqueue.c:844
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052b53c)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive
  - ipc/mqueue.c:__arm64_sys_mq_timedsend
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
In ipc/mqueue.c (c06e4cb8)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000676e20)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
In ipc/mqueue.c (ffffffe00038dfd0)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143bd2b)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142c79b)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81437ecb)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144e44b)
Location: ipc/mqueue.c:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ktime_t *expires</code>
</li>
<li>
<b>Param reordered. </b>
<code>u_abs_timeout, expires, ts</code> ➡️ <code>u_abs_timeout, ts</code>
</li>
</ul>
</details>
</li>
</ul>
