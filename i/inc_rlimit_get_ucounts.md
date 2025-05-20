# Function: <code>inc_rlimit_get_ucounts</code>

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
long int inc_rlimit_get_ucounts(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea3e0)
Location: kernel/ucount.c:308
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff810ea3e0-ffffffff810ea4d1: inc_rlimit_get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int inc_rlimit_get_ucounts(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff811050b0)
Location: kernel/ucount.c:314
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff811050b0-ffffffff811051d4: inc_rlimit_get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int inc_rlimit_get_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112ab00)
Location: kernel/ucount.c:310
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff8112ab00-ffffffff8112ac24: inc_rlimit_get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int inc_rlimit_get_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137c40)
Location: kernel/ucount.c:310
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff81137c40-ffffffff81137e37: inc_rlimit_get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int inc_rlimit_get_ucounts(struct ucounts *ucounts, enum rlimit_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142e50)
Location: kernel/ucount.c:311
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
```
**Symbols:**

```
ffffffff81142e50-ffffffff81143047: inc_rlimit_get_ucounts (STB_GLOBAL)
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
