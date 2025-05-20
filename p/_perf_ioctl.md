# Function: <code>_perf_ioctl</code>

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
In kernel/events/core.c (ffffffff811825a4)
Location: kernel/events/core.c:4257
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff81194434)
Location: kernel/events/core.c:4534
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811a3e14)
Location: kernel/events/core.c:4631
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811ab414)
Location: kernel/events/core.c:4723
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811bed34)
Location: kernel/events/core.c:4674
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dee40)
Location: kernel/events/core.c:5014
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811dee40-ffffffff811df52c: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ef270)
Location: kernel/events/core.c:5023
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811ef270-ffffffff811ef969: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206b90)
Location: kernel/events/core.c:5069
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81206b90-ffffffff81207183: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81213f00)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81213f00-ffffffff812144f3: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240120)
Location: kernel/events/core.c:5422
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81240120-ffffffff8124051a: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124a670)
Location: kernel/events/core.c:5501
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8124a670-ffffffff8124aa74: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124e7b0)
Location: kernel/events/core.c:5585
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8124e7b0-ffffffff8124ee5a: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c620)
Location: kernel/events/core.c:5690
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8128c620-ffffffff8128cd21: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e1230)
Location: kernel/events/core.c:5588
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff812e1230-ffffffff812e19ad: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349790)
Location: kernel/events/core.c:5806
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81349790-ffffffff81349f05: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a7a0)
Location: kernel/events/core.c:5806
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8137a7a0-ffffffff8137af35: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a39a0)
Location: kernel/events/core.c:5879
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff813a39a0-ffffffff813a4135: _perf_ioctl (STB_LOCAL)
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
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029df28)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffff80001029df28-ffff80001029e54c: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cd708)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
c04cd708-c04cdd48: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034ed70)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
c00000000034ed70-c00000000034f5a4: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8ecc)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffe0001c8ecc-ffffffe0001c92f4: _perf_ioctl (STB_LOCAL)
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
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c550)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8120c550-ffffffff8120cb43: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff320)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811ff320-ffffffff811ff913: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a2f0)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8120a2f0-ffffffff8120a8e3: _perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int _perf_ioctl(struct perf_event *event, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812190c0)
Location: kernel/events/core.c:5164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff812190c0-ffffffff812196bb: _perf_ioctl (STB_LOCAL)
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
