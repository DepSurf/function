# Function: <code>detach_if_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct tvec_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810eb9d0)
Location: kernel/time/timer.c:733
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer
```
**Symbols:**

```
ffffffff810eb9d0-ffffffff810ebac5: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f27d0)
Location: kernel/time/timer.c:831
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:del_timer
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810f27d0-ffffffff810f2897: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f9950)
Location: kernel/time/timer.c:831
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:del_timer
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810f9950-ffffffff810f9a17: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbe80)
Location: kernel/time/timer.c:797
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810fbe80-ffffffff810fbf46: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81106770)
Location: kernel/time/timer.c:806
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81106770-ffffffff81106839: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811130f0)
Location: kernel/time/timer.c:823
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff811130f0-ffffffff811131b9: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d400)
Location: kernel/time/timer.c:822
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8111d400-ffffffff8111d4c9: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811280c0)
Location: kernel/time/timer.c:817
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff811280c0-ffffffff81128185: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81134060)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81134060-ffffffff81134125: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811441e0)
Location: kernel/time/timer.c:829
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811441e0-ffffffff811442a6: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140790)
Location: kernel/time/timer.c:831
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81140790-ffffffff81140840: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141910)
Location: kernel/time/timer.c:833
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81141910-ffffffff811419c0: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81164e50)
Location: kernel/time/timer.c:833
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81164e50-ffffffff81164efd: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81198a20)
Location: kernel/time/timer.c:886
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81198a20-ffffffff81198b01: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d6dd0)
Location: kernel/time/timer.c:886
Inline: False
Direct callers:
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811d6dd0-ffffffff811d6eb1: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb260)
Location: kernel/time/timer.c:886
Inline: False
Direct callers:
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811eb260-ffffffff811eb341: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201290)
Location: kernel/time/timer.c:883
Inline: False
Direct callers:
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81201290-ffffffff81201371: detach_if_pending (STB_LOCAL)
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
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019eab0)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffff80001019eab0-ffff80001019ebdc: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7464)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
c03e7464-c03e757c: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fc410)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
c0000000001fc410-c0000000001fc598: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012bd20)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffe00012bd20-ffffffe00012be0c: detach_if_pending (STB_LOCAL)
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
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c810)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8112c810-ffffffff8112c8d5: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f080)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8111f080-ffffffff8111f145: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a530)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8112a530-ffffffff8112a5f5: detach_if_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list *timer, struct timer_base *base, bool clear_pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137af0)
Location: kernel/time/timer.c:821
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:try_to_del_timer_sync
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81137af0-ffffffff81137bd5: detach_if_pending (STB_LOCAL)
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
<b>Param type changed. </b>
<code>struct tvec_base *base</code> ➡️ <code>struct timer_base *base</code>
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
