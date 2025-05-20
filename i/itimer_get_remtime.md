# Function: <code>itimer_get_remtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f0060)
Location: kernel/time/itimer.c:27
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_setitimer
```
**Symbols:**

```
ffffffff810f0060-ffffffff810f00b0: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f7090)
Location: kernel/time/itimer.c:27
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff810f7090-ffffffff810f70e0: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81109750)
Location: kernel/time/itimer.c:27
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff81109750-ffffffff811097a0: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8110b550)
Location: kernel/time/itimer.c:30
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff8110b550-ffffffff8110b5a6: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811167a0)
Location: kernel/time/itimer.c:31
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff811167a0-ffffffff811167f6: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81123040)
Location: kernel/time/itimer.c:31
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff81123040-ffffffff81123090: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112e720)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff8112e720-ffffffff8112e770: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811391c0)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff811391c0-ffffffff81139214: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81144e60)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff81144e60-ffffffff81144eb4: itimer_get_remtime (STB_LOCAL)
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
In kernel/time/itimer.c (ffffffff81154bbf)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff81150e3f)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff8115226f)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff8117683f)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff811abcbe)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff811ebf5e)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff8120068e)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
In kernel/time/itimer.c (ffffffff81216b2e)
Location: kernel/time/itimer.c:29
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
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
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffff8000101af4d8)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffff8000101af4d8-ffff8000101af548: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c03fa3a4)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
c03fa3a4-c03fa450: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c000000000213d50)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
c000000000213d50-c000000000213e28: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffe000138b54)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffe000138b54-ffffffe000138baa: itimer_get_remtime (STB_LOCAL)
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
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113d610)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff8113d610-ffffffff8113d664: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81130160)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff81130160-ffffffff811301b4: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113b330)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff8113b330-ffffffff8113b384: itimer_get_remtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timeval itimer_get_remtime(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81147de0)
Location: kernel/time/itimer.c:29
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
```
**Symbols:**

```
ffffffff81147de0-ffffffff81147e34: itimer_get_remtime (STB_LOCAL)
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
