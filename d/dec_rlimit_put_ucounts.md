# Function: <code>dec_rlimit_put_ucounts</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dec_rlimit_put_ucounts(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea3c0)
Location: kernel/ucount.c:303
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff810ea3c0-ffffffff810ea3d4: dec_rlimit_put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dec_rlimit_put_ucounts(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81105090)
Location: kernel/ucount.c:309
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff81105090-ffffffff811050ae: dec_rlimit_put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dec_rlimit_put_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112aad0)
Location: kernel/ucount.c:305
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff8112aad0-ffffffff8112aaee: dec_rlimit_put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dec_rlimit_put_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137c10)
Location: kernel/ucount.c:305
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff81137c10-ffffffff81137c2e: dec_rlimit_put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dec_rlimit_put_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142e20)
Location: kernel/ucount.c:306
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff81142e20-ffffffff81142e3e: dec_rlimit_put_ucounts (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum ucount_type type</code> ➡️ <code>enum rlimit_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
