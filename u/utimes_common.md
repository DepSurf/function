# Function: <code>utimes_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int utimes_common(struct path *path, struct timespec *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81240c20)
Location: fs/utimes.c:51
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81240c20-ffffffff81240e08: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int utimes_common(struct path *path, struct timespec *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81268f60)
Location: fs/utimes.c:51
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81268f60-ffffffff8126913b: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int utimes_common(const struct path *path, struct timespec *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8127bf40)
Location: fs/utimes.c:51
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff8127bf40-ffffffff8127c0eb: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int utimes_common(const struct path *path, struct timespec *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81289270)
Location: fs/utimes.c:47
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81289270-ffffffff8128940a: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int utimes_common(const struct path *path, struct timespec *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812abd90)
Location: fs/utimes.c:48
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff812abd90-ffffffff812abf2d: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff812d2a40)
Location: fs/utimes.c:48
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff812d2a40-ffffffff812d2c08: utimes_common.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff812e7e20)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff812e7e20-ffffffff812e7fe8: utimes_common.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff81306730)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81306730-ffffffff813068f7: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff81319790)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81319790-ffffffff81319953: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int utimes_common(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81353740)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81353740-ffffffff813538fc: utimes_common (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffff8000103d0770)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffff8000103d0770-ffff8000103d091c: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int utimes_common(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c05abaf8)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
c05abaf8-c05abcb0: utimes_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (c0000000004d3040)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
c0000000004d3040-c0000000004d3298: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffe00028c9be)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffe00028c9be-ffffffe00028cb2e: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff81311d70)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81311d70-ffffffff81311f33: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff81302980)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81302980-ffffffff81302b43: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff8130fb60)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff8130fb60-ffffffff8130fd23: utimes_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/utimes.c (ffffffff81321360)
Location: fs/utimes.c:19
Inline: True
Direct callers:
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
```
**Symbols:**

```
ffffffff81321360-ffffffff81321523: utimes_common.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
