# Function: <code>timerfd_resume</code>

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
void timerfd_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813d3130)
Location: fs/timerfd.c:129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff813d3130-ffffffff813d3153: timerfd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void timerfd_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8145c660)
Location: fs/timerfd.c:129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff8145c660-ffffffff8145c68f: timerfd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void timerfd_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff814ebdb0)
Location: fs/timerfd.c:129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff814ebdb0-ffffffff814ebddf: timerfd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void timerfd_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81522b50)
Location: fs/timerfd.c:129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81522b50-ffffffff81522b7f: timerfd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void timerfd_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81557170)
Location: fs/timerfd.c:129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81557170-ffffffff8155719f: timerfd_resume (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
