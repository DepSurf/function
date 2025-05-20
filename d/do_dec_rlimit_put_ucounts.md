# Function: <code>do_dec_rlimit_put_ucounts</code>

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
void do_dec_rlimit_put_ucounts(struct ucounts *ucounts, struct ucounts *last, enum ucount_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea170)
Location: kernel/ucount.c:290
Inline: False
Direct callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:dec_rlimit_put_ucounts
```
**Symbols:**

```
ffffffff810ea170-ffffffff810ea1e5: do_dec_rlimit_put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts *ucounts, struct ucounts *last, enum ucount_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104dd0)
Location: kernel/ucount.c:296
Inline: False
Direct callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:dec_rlimit_put_ucounts
```
**Symbols:**

```
ffffffff81104dd0-ffffffff81104e53: do_dec_rlimit_put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts *ucounts, struct ucounts *last, enum rlimit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a6f0)
Location: kernel/ucount.c:292
Inline: False
Direct callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:dec_rlimit_put_ucounts
```
**Symbols:**

```
ffffffff8112a6f0-ffffffff8112a773: do_dec_rlimit_put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts *ucounts, struct ucounts *last, enum rlimit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137740)
Location: kernel/ucount.c:292
Inline: False
Direct callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:dec_rlimit_put_ucounts
```
**Symbols:**

```
ffffffff81137740-ffffffff811377f7: do_dec_rlimit_put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts *ucounts, struct ucounts *last, enum rlimit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142950)
Location: kernel/ucount.c:293
Inline: False
Direct callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:dec_rlimit_put_ucounts
```
**Symbols:**

```
ffffffff81142950-ffffffff81142a07: do_dec_rlimit_put_ucounts (STB_LOCAL)
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
