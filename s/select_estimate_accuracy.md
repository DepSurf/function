# Function: <code>select_estimate_accuracy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int select_estimate_accuracy(struct timespec *tv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff81220e80)
Location: fs/select.c:73
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
Direct callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81220e80-ffffffff81220f77: select_estimate_accuracy.part.6 (STB_LOCAL)
ffffffff81220f80-ffffffff81220fa2: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 select_estimate_accuracy(struct timespec *tv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff81249cb5)
Location: fs/select.c:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81248b10-ffffffff81248bfa: select_estimate_accuracy.part.8 (STB_LOCAL)
ffffffff81248c00-ffffffff81248c22: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 select_estimate_accuracy(struct timespec *tv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8125cc85)
Location: fs/select.c:74
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8125bb40-ffffffff8125bc2a: select_estimate_accuracy.part.8 (STB_LOCAL)
ffffffff8125bc30-ffffffff8125bc52: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81268ae0)
Location: fs/select.c:74
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81268ae0-ffffffff81268be6: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128b3a0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8128b3a0-ffffffff8128b4a6: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b1bd0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812b1bd0-ffffffff812b1cce: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c6cf0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812c6cf0-ffffffff812c6dee: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e3870)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812e3870-ffffffff812e396e: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f52b0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812f52b0-ffffffff812f53ae: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132d870)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8132d870-ffffffff8132d96e: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff813390d0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff813390d0-ffffffff813391ce: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133f690)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8133f690-ffffffff8133f78b: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138d020)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8138d020-ffffffff8138d11b: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140e360)
Location: fs/select.c:76
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8140e360-ffffffff8140e48a: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81498ee0)
Location: fs/select.c:76
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81498ee0-ffffffff8149900a: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cdf70)
Location: fs/select.c:76
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff814cdf70-ffffffff814ce09a: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815008b0)
Location: fs/select.c:76
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff815008b0-ffffffff815009da: select_estimate_accuracy (STB_GLOBAL)
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
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a25e8)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffff8000103a25e8-ffff8000103a26f4: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0584fd0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
c0584fd0-c0585158: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049bf40)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
c00000000049bf40-c00000000049c0bc: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026aa0a)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffe00026aa0a-ffffffe00026aada: select_estimate_accuracy (STB_GLOBAL)
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
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed890)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812ed890-ffffffff812ed98e: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812de4c0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812de4c0-ffffffff812de5be: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eb6a0)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812eb6a0-ffffffff812eb79e: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec64 *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fc690)
Location: fs/select.c:75
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff812fc690-ffffffff812fc78e: select_estimate_accuracy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *tv</code> ➡️ <code>struct timespec64 *tv</code>
</li>
</ul>
</details>
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
