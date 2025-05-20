# Function: <code>perf_event_set_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811816b0)
Location: kernel/events/core.c:8132
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811816b0-ffffffff811817ba: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811934a0)
Location: kernel/events/core.c:9260
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811934a0-ffffffff811935d0: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2c80)
Location: kernel/events/core.c:9467
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811a2c80-ffffffff811a2db0: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811aa290)
Location: kernel/events/core.c:9690
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811aa290-ffffffff811aa3be: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bdb80)
Location: kernel/events/core.c:9717
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811bdb80-ffffffff811bdcae: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dddc0)
Location: kernel/events/core.c:10246
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811dddc0-ffffffff811ddeee: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ee1c0)
Location: kernel/events/core.c:10289
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811ee1c0-ffffffff811ee2f2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205c00)
Location: kernel/events/core.c:10636
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81205c00-ffffffff81205d32: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212f90)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81212f90-ffffffff812130c2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124048d)
Location: kernel/events/core.c:11332
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123f0a0-ffffffff8123f1d2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124a9e2)
Location: kernel/events/core.c:11616
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812494a0-ffffffff812495d2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ec67)
Location: kernel/events/core.c:11783
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8124d660-ffffffff8124d792: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128cb2e)
Location: kernel/events/core.c:11895
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81287270-ffffffff812873a2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e17cc)
Location: kernel/events/core.c:11843
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812dd500-ffffffff812dd69c: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349d24)
Location: kernel/events/core.c:12140
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81345870-ffffffff81345a0c: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137ad38)
Location: kernel/events/core.c:12180
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81376920-ffffffff81376abc: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a3f38)
Location: kernel/events/core.c:12264
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8139fbb0-ffffffff8139fd4c: perf_event_set_output (STB_LOCAL)
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
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029d360)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff80001029d360-ffff80001029d488: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ccae4)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c04ccae4-c04ccc04: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034ddf0)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c00000000034ddf0-c00000000034df38: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c60f8)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffe0001c60f8-ffffffe0001c61ee: perf_event_set_output (STB_LOCAL)
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
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b5e0)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8120b5e0-ffffffff8120b712: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe3b0)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811fe3b0-ffffffff811fe4e2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209380)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81209380-ffffffff812094b2: perf_event_set_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_set_output(struct perf_event *event, struct perf_event *output_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81218120)
Location: kernel/events/core.c:10737
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81218120-ffffffff81218252: perf_event_set_output (STB_LOCAL)
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
