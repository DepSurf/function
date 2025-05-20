# Function: <code>__compat_get_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec *ts, const struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110f790)
Location: kernel/compat.c:143
Inline: False
Direct callers:
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:get_compat_itimerspec
```
**Symbols:**

```
ffffffff8110f790-ffffffff8110f7e6: __compat_get_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec *ts, const struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81116f10)
Location: kernel/compat.c:143
Inline: False
Direct callers:
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:compat_get_timespec
```
**Symbols:**

```
ffffffff81116f10-ffffffff81116f63: __compat_get_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec *ts, const struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e650)
Location: kernel/compat.c:143
Inline: False
Direct callers:
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:compat_get_timespec
```
**Symbols:**

```
ffffffff8111e650-ffffffff8111e6a3: __compat_get_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec *ts, const struct compat_timespec *cts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811202c0)
Location: kernel/compat.c:109
Inline: False
Direct callers:
  - kernel/compat.c:get_compat_itimerspec
  - kernel/compat.c:get_compat_itimerspec
```
**Symbols:**

```
ffffffff811202c0-ffffffff81120313: __compat_get_timespec (STB_LOCAL)
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
In kernel/compat.c (ffffffff8112be22)
Location: kernel/compat.c:109
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
In kernel/compat.c (ffffffff8113a5e5)
Location: kernel/compat.c:110
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
In kernel/compat.c (ffffffff81145e45)
Location: kernel/compat.c:110
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
In kernel/compat.c (ffffffff81151189)
Location: kernel/compat.c:43
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
In kernel/compat.c (ffffffff8115cdf9)
Location: kernel/compat.c:43
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
In kernel/compat.c (ffff8000101cbe34)
Location: kernel/compat.c:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_get_timespec
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
In kernel/compat.c (c000000000236990)
Location: kernel/compat.c:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_get_timespec
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
In kernel/compat.c (ffffffff81155419)
Location: kernel/compat.c:43
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
In kernel/compat.c (ffffffff81148739)
Location: kernel/compat.c:43
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
In kernel/compat.c (ffffffff811531e9)
Location: kernel/compat.c:43
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
In kernel/compat.c (ffffffff811600e9)
Location: kernel/compat.c:43
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
