# Function: <code>perf_group_attach</code>

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
In kernel/events/core.c (ffffffff81179b92)
Location: kernel/events/core.c:1368
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
In kernel/events/core.c (ffffffff8118c044)
Location: kernel/events/core.c:1621
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
In kernel/events/core.c (ffffffff8119b527)
Location: kernel/events/core.c:1627
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
In kernel/events/core.c (ffffffff811a30bb)
Location: kernel/events/core.c:1640
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
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5330)
Location: kernel/events/core.c:1639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811b5330-ffffffff811b53b9: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d41e0)
Location: kernel/events/core.c:1821
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811d41e0-ffffffff811d4283: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e46d0)
Location: kernel/events/core.c:1821
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811e46d0-ffffffff811e4773: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb9e0)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811fb9e0-ffffffff811fba87: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208c60)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81208c60-ffffffff81208d07: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81232ca0)
Location: kernel/events/core.c:1950
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81232ca0-ffffffff81232d40: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c860)
Location: kernel/events/core.c:1974
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8123c860-ffffffff8123c900: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241510)
Location: kernel/events/core.c:1957
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81241510-ffffffff812415b0: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127bf60)
Location: kernel/events/core.c:2025
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8127bf60-ffffffff8127c000: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cfcf0)
Location: kernel/events/core.c:1936
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff812cfcf0-ffffffff812cfdcb: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813397e0)
Location: kernel/events/core.c:1938
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff813397e0-ffffffff813398ff: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136a8a0)
Location: kernel/events/core.c:1938
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8136a8a0-ffffffff8136a9bf: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138e3b0)
Location: kernel/events/core.c:1974
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8138e3b0-ffffffff8138e492: perf_group_attach (STB_LOCAL)
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
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010292480)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffff800010292480-ffff800010292544: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c08d4)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c04c08d4-c04c09c0: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e1d0)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c00000000033e1d0-c00000000033e2c8: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c38fe)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffe0001c38fe-ffffffe0001c39a4: perf_group_attach (STB_LOCAL)
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
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201280)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81201280-ffffffff81201327: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f3fd0)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811f3fd0-ffffffff811f4077: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff050)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811ff050-ffffffff811ff0f7: perf_group_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_group_attach(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120e0e0)
Location: kernel/events/core.c:1823
Inline: False
Direct callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8120e0e0-ffffffff8120e187: perf_group_attach (STB_LOCAL)
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
