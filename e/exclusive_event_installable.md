# Function: <code>exclusive_event_installable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81179fa0)
Location: kernel/events/core.c:3675
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff81179fa0-ffffffff81179ff0: exclusive_event_installable.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811889d0)
Location: kernel/events/core.c:3946
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811889d0-ffffffff81188a33: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81197db0)
Location: kernel/events/core.c:4043
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff81197db0-ffffffff81197e13: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f8d0)
Location: kernel/events/core.c:4130
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8119f8d0-ffffffff8119f930: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3240)
Location: kernel/events/core.c:4064
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811b3240-ffffffff811b32a0: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d29b0)
Location: kernel/events/core.c:4399
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811d29b0-ffffffff811d2a10: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e2cb0)
Location: kernel/events/core.c:4400
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811e2cb0-ffffffff811e2d10: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9e50)
Location: kernel/events/core.c:4424
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff811f9e50-ffffffff811f9eb7: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206f20)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff81206f20-ffffffff81206f87: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230430)
Location: kernel/events/core.c:4745
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff81230430-ffffffff81230497: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a090)
Location: kernel/events/core.c:4824
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff8123a090-ffffffff8123a0f7: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e8c0)
Location: kernel/events/core.c:4908
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff8123e8c0-ffffffff8123e929: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812793a0)
Location: kernel/events/core.c:5014
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff812793a0-ffffffff81279409: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc3b0)
Location: kernel/events/core.c:4912
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff812cc3b0-ffffffff812cc431: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81333f90)
Location: kernel/events/core.c:5124
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff81333f90-ffffffff81334011: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81364d00)
Location: kernel/events/core.c:5124
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff81364d00-ffffffff81364d81: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138dcd0)
Location: kernel/events/core.c:5173
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff8138dcd0-ffffffff8138dd51: exclusive_event_installable (STB_LOCAL)
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
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290bf8)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffff800010290bf8-ffff800010290c54: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0098)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
c04c0098-c04c0118: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033d940)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
c00000000033d940-c00000000033d9b8: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c355a)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffe0001c355a-ffffffe0001c35a6: exclusive_event_installable (STB_LOCAL)
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
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff540)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff811ff540-ffffffff811ff5a7: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2290)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff811f2290-ffffffff811f22f7: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd310)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff811fd310-ffffffff811fd377: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c070)
Location: kernel/events/core.c:4519
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_install_in_context
```
**Symbols:**

```
ffffffff8120c070-ffffffff8120c0d7: exclusive_event_installable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
