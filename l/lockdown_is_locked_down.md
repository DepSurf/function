# Function: <code>lockdown_is_locked_down</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814b39bf)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffff814b3990-ffffffff814b39d9: lockdown_is_locked_down (STB_LOCAL)
ffffffff814b3a2f-ffffffff814b3a53: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81512eef)
Location: security/lockdown/lockdown.c:58
Inline: True
```
**Symbols:**

```
ffffffff81512ec0-ffffffff81512f09: lockdown_is_locked_down (STB_LOCAL)
ffffffff81512f63-ffffffff81512f87: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff815300bf)
Location: security/lockdown/lockdown.c:58
Inline: True
```
**Symbols:**

```
ffffffff81530090-ffffffff815300d9: lockdown_is_locked_down (STB_LOCAL)
ffffffff81bf19ab-ffffffff81bf19cf: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff815362bf)
Location: security/lockdown/lockdown.c:58
Inline: True
```
**Symbols:**

```
ffffffff81536290-ffffffff815362d9: lockdown_is_locked_down (STB_LOCAL)
ffffffff81be39c9-ffffffff81be39ed: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81594960)
Location: security/lockdown/lockdown.c:58
Inline: True
```
**Symbols:**

```
ffffffff81594960-ffffffff81594a03: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81636a70)
Location: security/lockdown/lockdown.c:58
Inline: False
```
**Symbols:**

```
ffffffff81636a70-ffffffff81636b0b: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff816edbf0)
Location: security/lockdown/lockdown.c:59
Inline: False
```
**Symbols:**

```
ffffffff816edbf0-ffffffff816edca3: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81728000)
Location: security/lockdown/lockdown.c:59
Inline: False
```
**Symbols:**

```
ffffffff81728000-ffffffff817280b3: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81769330)
Location: security/lockdown/lockdown.c:59
Inline: False
```
**Symbols:**

```
ffffffff81769330-ffffffff817693e3: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffff8000105ab720)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffff8000105ab720-ffff8000105ab7b8: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c075b2b8)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
c075b2b8-c075b35c: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c0000000007297b0)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
c0000000007297b0-c000000000729884: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffe0003f4244)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffe0003f4244-ffffffe0003f42c6: lockdown_is_locked_down (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814abf9f)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffff814abf70-ffffffff814abfb9: lockdown_is_locked_down (STB_LOCAL)
ffffffff814ac00f-ffffffff814ac033: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff8149c9bf)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffff8149c990-ffffffff8149c9d9: lockdown_is_locked_down (STB_LOCAL)
ffffffff8149ca2f-ffffffff8149ca53: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814a803f)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffff814a8010-ffffffff814a8059: lockdown_is_locked_down (STB_LOCAL)
ffffffff814a80af-ffffffff814a80d3: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lockdown_is_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814c09cf)
Location: security/lockdown/lockdown.c:85
Inline: True
```
**Symbols:**

```
ffffffff814c09a0-ffffffff814c09e9: lockdown_is_locked_down (STB_LOCAL)
ffffffff814c0a3f-ffffffff814c0a63: lockdown_is_locked_down.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
