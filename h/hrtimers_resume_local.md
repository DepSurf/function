# Function: <code>hrtimers_resume_local</code>

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
void hrtimers_resume_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167f40)
Location: kernel/time/hrtimer.c:1004
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffff81167f40-ffffffff81167f52: hrtimers_resume_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hrtimers_resume_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b930)
Location: kernel/time/hrtimer.c:1004
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffff8119b930-ffffffff8119b948: hrtimers_resume_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hrtimers_resume_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811da210)
Location: kernel/time/hrtimer.c:1004
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffff811da210-ffffffff811da228: hrtimers_resume_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hrtimers_resume_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ee740)
Location: kernel/time/hrtimer.c:1006
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffff811ee740-ffffffff811ee758: hrtimers_resume_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hrtimers_resume_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff812048c0)
Location: kernel/time/hrtimer.c:1006
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffff812048c0-ffffffff812048d8: hrtimers_resume_local (STB_GLOBAL)
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
