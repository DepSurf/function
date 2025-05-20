# Function: <code>perf_copy_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811817f6)
Location: kernel/events/core.c:8001
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119361f)
Location: kernel/events/core.c:9129
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2dff)
Location: kernel/events/core.c:9336
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811aa40f)
Location: kernel/events/core.c:9557
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
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
In kernel/events/core.c (ffffffff811bdcff)
Location: kernel/events/core.c:9584
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d88e0)
Location: kernel/events/core.c:10110
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d88e0-ffffffff811d8b4f: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e9a70)
Location: kernel/events/core.c:10153
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e9a70-ffffffff811e9cdf: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200d90)
Location: kernel/events/core.c:10500
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81200d90-ffffffff81201025: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208680)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81208680-ffffffff8120895d: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81233cb0)
Location: kernel/events/core.c:11217
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81233cb0-ffffffff81233fb7: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123da10)
Location: kernel/events/core.c:11501
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123da10-ffffffff8123dd17: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812423a0)
Location: kernel/events/core.c:11656
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812423a0-ffffffff81242717: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127ccb0)
Location: kernel/events/core.c:11768
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8127ccb0-ffffffff8127d027: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d0710)
Location: kernel/events/core.c:11707
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812d0710-ffffffff812d0a75: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81339b10)
Location: kernel/events/core.c:12004
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81339b10-ffffffff81339e79: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136abd0)
Location: kernel/events/core.c:12044
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8136abd0-ffffffff8136af41: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81393810)
Location: kernel/events/core.c:12128
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81393810-ffffffff81393b81: perf_copy_attr (STB_LOCAL)
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
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010298750)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff800010298750-ffff800010298b08: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c5398)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c04c5398-c04c56e0: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000343f20)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c000000000343f20-c000000000344398: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c7f06)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffe0001c7f06-ffffffe0001c814e: perf_copy_attr (STB_LOCAL)
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
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200ca0)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81200ca0-ffffffff81200f7d: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f39f0)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811f39f0-ffffffff811f3ccd: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fea70)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811fea70-ffffffff811fed4d: perf_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr *uattr, struct perf_event_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120db00)
Location: kernel/events/core.c:10630
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8120db00-ffffffff8120dddd: perf_copy_attr (STB_LOCAL)
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
