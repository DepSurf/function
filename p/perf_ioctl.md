# Function: <code>perf_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81182570)
Location: kernel/events/core.c:4324
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81182570-ffffffff81182a24: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81194400)
Location: kernel/events/core.c:4614
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81194400-ffffffff8119489b: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3de0)
Location: kernel/events/core.c:4711
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811a3de0-ffffffff811a42f6: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ab3e0)
Location: kernel/events/core.c:4803
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811ab3e0-ffffffff811ab962: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bed00)
Location: kernel/events/core.c:4754
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811bed00-ffffffff811bf2da: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811df530)
Location: kernel/events/core.c:5108
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811df530-ffffffff811df581: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ef970)
Location: kernel/events/core.c:5117
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811ef970-ffffffff811ef9c1: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207190)
Location: kernel/events/core.c:5163
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81207190-ffffffff812071e4: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81214500)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81214500-ffffffff81214554: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812405b4)
Location: kernel/events/core.c:5522
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81240520-ffffffff81240585: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ab14)
Location: kernel/events/core.c:5601
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8124aa80-ffffffff8124aae5: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124eef4)
Location: kernel/events/core.c:5685
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8124ee60-ffffffff8124eec5: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128cdc4)
Location: kernel/events/core.c:5805
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8128cd30-ffffffff8128cd95: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e1a58)
Location: kernel/events/core.c:5703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff812e19b0-ffffffff812e1a24: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349fd8)
Location: kernel/events/core.c:5921
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff81349f20-ffffffff81349f94: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137b008)
Location: kernel/events/core.c:5921
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8137af50-ffffffff8137afc4: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a4208)
Location: kernel/events/core.c:5994
Inline: True
Inline callers:
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff813a4150-ffffffff813a41c4: perf_ioctl (STB_LOCAL)
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
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029e550)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffff80001029e550-ffff80001029e5b0: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cdd48)
Location: kernel/events/core.c:5258
Inline: False
```
**Symbols:**

```
c04cdd48-c04cdd98: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034f5b0)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
c00000000034f5b0-c00000000034f628: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c92f4)
Location: kernel/events/core.c:5258
Inline: False
```
**Symbols:**

```
ffffffe0001c92f4-ffffffe0001c9350: perf_ioctl (STB_LOCAL)
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
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cb50)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8120cb50-ffffffff8120cba4: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff920)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff811ff920-ffffffff811ff974: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a8f0)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff8120a8f0-ffffffff8120a944: perf_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int perf_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812196c0)
Location: kernel/events/core.c:5258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_compat_ioctl
```
**Symbols:**

```
ffffffff812196c0-ffffffff81219714: perf_ioctl (STB_LOCAL)
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
