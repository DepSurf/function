# Function: <code>__compat_put_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __compat_put_timespec(const struct timespec *ts, struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110f7f0)
Location: kernel/compat.c:150
Inline: False
Direct callers:
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:put_compat_itimerspec
```
**Symbols:**

```
ffffffff8110f7f0-ffffffff8110f841: __compat_put_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __compat_put_timespec(const struct timespec *ts, struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81116f70)
Location: kernel/compat.c:150
Inline: False
Direct callers:
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:compat_put_timespec
```
**Symbols:**

```
ffffffff81116f70-ffffffff81116fbd: __compat_put_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __compat_put_timespec(const struct timespec *ts, struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e6b0)
Location: kernel/compat.c:150
Inline: False
Direct callers:
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:compat_put_timespec
```
**Symbols:**

```
ffffffff8111e6b0-ffffffff8111e6fd: __compat_put_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __compat_put_timespec(const struct timespec *ts, struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120320)
Location: kernel/compat.c:116
Inline: False
Direct callers:
  - kernel/compat.c:put_compat_itimerspec
  - kernel/compat.c:put_compat_itimerspec
```
**Symbols:**

```
ffffffff81120320-ffffffff8112036d: __compat_put_timespec (STB_LOCAL)
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
In kernel/compat.c (ffffffff8112beab)
Location: kernel/compat.c:116
Inline: True
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
In kernel/compat.c (ffffffff8113a66e)
Location: kernel/compat.c:117
Inline: True
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
In kernel/compat.c (ffffffff81145ece)
Location: kernel/compat.c:117
Inline: True
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
In kernel/compat.c (ffffffff811512a2)
Location: kernel/compat.c:50
Inline: True
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
In kernel/compat.c (ffffffff8115cf03)
Location: kernel/compat.c:50
Inline: True
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/compat.c (ffff8000101cbb54)
Location: kernel/compat.c:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_timespec
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236630)
Location: kernel/compat.c:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_timespec
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155523)
Location: kernel/compat.c:50
Inline: True
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
In kernel/compat.c (ffffffff81148843)
Location: kernel/compat.c:50
Inline: True
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
In kernel/compat.c (ffffffff811532f3)
Location: kernel/compat.c:50
Inline: True
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
In kernel/compat.c (ffffffff811601f3)
Location: kernel/compat.c:50
Inline: True
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
</ul>
