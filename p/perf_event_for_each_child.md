# Function: <code>perf_event_for_each_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178800)
Location: kernel/events/core.c:4118
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81178800-ffffffff81178899: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81188dd0)
Location: kernel/events/core.c:4426
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81188dd0-ffffffff81188e69: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811981a0)
Location: kernel/events/core.c:4523
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811981a0-ffffffff81198239: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119ff80)
Location: kernel/events/core.c:4615
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8119ff80-ffffffff8119fffa: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b38b0)
Location: kernel/events/core.c:4566
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811b38b0-ffffffff811b392e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2d90)
Location: kernel/events/core.c:4904
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d2d90-ffffffff811d2e0e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e2fe0)
Location: kernel/events/core.c:4905
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e2fe0-ffffffff811e305e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa1b0)
Location: kernel/events/core.c:4948
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811fa1b0-ffffffff811fa22e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207280)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81207280-ffffffff812072fe: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123902f)
Location: kernel/events/core.c:5293
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81230750-ffffffff812307ce: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242fcf)
Location: kernel/events/core.c:5372
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123a3b0-ffffffff8123a42e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124af37)
Location: kernel/events/core.c:5456
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123ebe0-ffffffff8123ec5e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81284527)
Location: kernel/events/core.c:5562
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81279610-ffffffff8127968e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d8948)
Location: kernel/events/core.c:5460
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812cc790-ffffffff812cc81f: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81340ee8)
Location: kernel/events/core.c:5678
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81334650-ffffffff813346df: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81371e78)
Location: kernel/events/core.c:5678
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81365390-ffffffff8136541f: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139b1e8)
Location: kernel/events/core.c:5751
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8138e4b0-ffffffff8138e53f: perf_event_for_each_child (STB_LOCAL)
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
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290da8)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff800010290da8-ffff800010290e28: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0b5c)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c04c0b5c-c04c0bfc: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e2d0)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c00000000033e2d0-c00000000033e3a8: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c39a4)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffe0001c39a4-ffffffe0001c3a0c: perf_event_for_each_child (STB_LOCAL)
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
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff8a0)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811ff8a0-ffffffff811ff91e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f25f0)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811f25f0-ffffffff811f266e: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd670)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811fd670-ffffffff811fd6ee: perf_event_for_each_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_for_each_child(struct perf_event *event, void (*func)(struct perf_event *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c4b0)
Location: kernel/events/core.c:5043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8120c4b0-ffffffff8120c52e: perf_event_for_each_child (STB_LOCAL)
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
