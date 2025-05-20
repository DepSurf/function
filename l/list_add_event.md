# Function: <code>list_add_event</code>

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
In kernel/events/core.c (ffffffff81179b29)
Location: kernel/events/core.c:1216
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
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
In kernel/events/core.c (ffffffff8118bfa9)
Location: kernel/events/core.c:1467
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
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
In kernel/events/core.c (ffffffff8119b479)
Location: kernel/events/core.c:1475
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
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
In kernel/events/core.c (ffffffff811a2ff1)
Location: kernel/events/core.c:1488
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b71a0)
Location: kernel/events/core.c:1482
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811b71a0-ffffffff811b734f: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d73e0)
Location: kernel/events/core.c:1668
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811d73e0-ffffffff811d75b1: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7810)
Location: kernel/events/core.c:1668
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811e7810-ffffffff811e79e1: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff050)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811ff050-ffffffff811ff221: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120bec0)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8120bec0-ffffffff8120c091: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231530)
Location: kernel/events/core.c:1793
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81231530-ffffffff81231714: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b1a0)
Location: kernel/events/core.c:1811
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8123b1a0-ffffffff8123b384: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f960)
Location: kernel/events/core.c:1794
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8123f960-ffffffff8123fb44: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a1b0)
Location: kernel/events/core.c:1862
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8127a1b0-ffffffff8127a3ec: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd700)
Location: kernel/events/core.c:1771
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff812cd700-ffffffff812cd8fd: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81335ed0)
Location: kernel/events/core.c:1769
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81335ed0-ffffffff8133607b: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366c20)
Location: kernel/events/core.c:1769
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81366c20-ffffffff81366dcb: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138fb80)
Location: kernel/events/core.c:1780
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8138fb80-ffffffff8138fd3a: list_add_event (STB_LOCAL)
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
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010298008)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffff800010298008-ffff8000102981a0: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c2138)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c04c2138-c04c232c: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033f310)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c00000000033f310-c00000000033f518: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3e22)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffe0001c3e22-ffffffe0001c3f88: list_add_event (STB_LOCAL)
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
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812044e0)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff812044e0-ffffffff812046b1: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f7270)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811f7270-ffffffff811f7441: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812022b0)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff812022b0-ffffffff81202481: list_add_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void list_add_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211b00)
Location: kernel/events/core.c:1670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81211b00-ffffffff81211cd1: list_add_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
