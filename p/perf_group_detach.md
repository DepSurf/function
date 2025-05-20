# Function: <code>perf_group_detach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811799b0)
Location: kernel/events/core.c:1454
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_free_event
```
**Symbols:**

```
ffffffff811799b0-ffffffff81179aee: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a3b0)
Location: kernel/events/core.c:1695
Inline: False
Direct callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8118a3b0-ffffffff8118a50f: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811997a0)
Location: kernel/events/core.c:1701
Inline: False
Direct callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811997a0-ffffffff811998ff: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1690)
Location: kernel/events/core.c:1714
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811a1690-ffffffff811a17ae: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5210)
Location: kernel/events/core.c:1711
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811b5210-ffffffff811b532e: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d4030)
Location: kernel/events/core.c:1893
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811d4030-ffffffff811d41df: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e4780)
Location: kernel/events/core.c:1893
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811e4780-ffffffff811e492f: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fba90)
Location: kernel/events/core.c:1895
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811fba90-ffffffff811fbc3f: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212000)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81212000-ffffffff81212285: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e220)
Location: kernel/events/core.c:2126
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8123e220-ffffffff8123e4ba: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812485e0)
Location: kernel/events/core.c:2165
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812485e0-ffffffff812488a6: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c4d0)
Location: kernel/events/core.c:2148
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8124c4d0-ffffffff8124c751: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81287e00)
Location: kernel/events/core.c:2216
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81287e00-ffffffff81288197: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dc620)
Location: kernel/events/core.c:2129
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812dc620-ffffffff812dc9db: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813449e0)
Location: kernel/events/core.c:2128
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff813449e0-ffffffff81344d66: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81375a80)
Location: kernel/events/core.c:2128
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81375a80-ffffffff81375e13: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139edb0)
Location: kernel/events/core.c:2165
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8139edb0-ffffffff8139f113: perf_group_detach (STB_LOCAL)
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
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029c4b0)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffff80001029c4b0-ffff80001029c724: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cba80)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
c04cba80-c04cbcd4: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034c920)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
c00000000034c920-c00000000034cc64: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cae34)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffe0001cae34-ffffffe0001cb05c: perf_group_detach (STB_LOCAL)
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
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a650)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8120a650-ffffffff8120a8d5: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd440)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811fd440-ffffffff811fd6c5: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812083f0)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812083f0-ffffffff81208675: perf_group_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81217190)
Location: kernel/events/core.c:1978
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81217190-ffffffff81217415: perf_group_detach (STB_LOCAL)
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
