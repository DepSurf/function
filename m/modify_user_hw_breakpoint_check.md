# Function: <code>modify_user_hw_breakpoint_check</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811e4160)
Location: kernel/events/hw_breakpoint.c:482
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e4160-ffffffff811e42f3: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811f45c0)
Location: kernel/events/hw_breakpoint.c:474
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811f45c0-ffffffff811f47f2: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (0)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8120c59a-ffffffff8120c5ad: modify_user_hw_breakpoint_check.cold (STB_LOCAL)
ffffffff8120c2b0-ffffffff8120c510: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812195b0)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812195b0-ffffffff81219810: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812453c0)
Location: kernel/events/hw_breakpoint.c:477
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812453c0-ffffffff8124564a: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124fa10)
Location: kernel/events/hw_breakpoint.c:477
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8124fa10-ffffffff8124fc9a: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812542e0)
Location: kernel/events/hw_breakpoint.c:477
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812542e0-ffffffff8125457a: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8128fd50)
Location: kernel/events/hw_breakpoint.c:478
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8128fd50-ffffffff8128ffea: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812e4dd0)
Location: kernel/events/hw_breakpoint.c:478
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812e4dd0-ffffffff812e5098: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134e5f0)
Location: kernel/events/hw_breakpoint.c:789
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8134e5f0-ffffffff8134e8c4: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8137f810)
Location: kernel/events/hw_breakpoint.c:789
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8137f810-ffffffff8137fa54: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff813a8a30)
Location: kernel/events/hw_breakpoint.c:761
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff813a8a30-ffffffff813a8c6c: modify_user_hw_breakpoint_check (STB_GLOBAL)
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
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffff8000102a47c0)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffff8000102a47c0-ffff8000102a4984: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c04d3d80)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c04d3d80-c04d3f2c: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c000000000357030)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c000000000357030-c000000000357270: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/hw_breakpoint.h:104
Inline: True
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
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81211c00)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81211c00-ffffffff81211e60: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81204990)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81204990-ffffffff81204bf0: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120f9a0)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8120f9a0-ffffffff8120fc00: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event *bp, struct perf_event_attr *attr, bool check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8121e8b0)
Location: kernel/events/hw_breakpoint.c:461
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8121e8b0-ffffffff8121eb10: modify_user_hw_breakpoint_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
