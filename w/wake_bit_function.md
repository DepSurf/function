# Function: <code>wake_bit_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int wake_bit_function(wait_queue_t *wait, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3a50)
Location: kernel/sched/wait.c:366
Inline: True
```
**Symbols:**

```
ffffffff810c3a50-ffffffff810c3ab2: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int wake_bit_function(wait_queue_t *wait, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c73e0)
Location: kernel/sched/wait.c:366
Inline: True
```
**Symbols:**

```
ffffffff810c73e0-ffffffff810c7435: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wake_bit_function(wait_queue_t *wait, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cd2b0)
Location: kernel/sched/wait.c:354
Inline: True
```
**Symbols:**

```
ffffffff810cd2b0-ffffffff810cd305: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810c9ba0)
Location: kernel/sched/wait_bit.c:23
Inline: False
```
**Symbols:**

```
ffffffff810c9ba0-ffffffff810c9bcd: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d13c0)
Location: kernel/sched/wait_bit.c:23
Inline: False
```
**Symbols:**

```
ffffffff810d13c0-ffffffff810d13ed: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9990)
Location: kernel/sched/wait_bit.c:20
Inline: False
```
**Symbols:**

```
ffffffff810d9990-ffffffff810d99bc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e3490)
Location: kernel/sched/wait_bit.c:20
Inline: False
```
**Symbols:**

```
ffffffff810e3490-ffffffff810e34bc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea0d0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810ea0d0-ffffffff810ea0fc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5aa0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810f5aa0-ffffffff810f5acc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff1e0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810ff1e0-ffffffff810ff20c: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fdce0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810fdce0-ffffffff810fdd0c: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff811000c0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff811000c0-ffffffff811000ec: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c160)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff8111c160-ffffffff8111c18c: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141f10)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff81141f10-ffffffff81141f81: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116d4a0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff8116d4a0-ffffffff8116d511: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117dcb0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff8117dcb0-ffffffff8117dd21: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ba00)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff8118ba00-ffffffff8118ba71: wake_bit_function (STB_GLOBAL)
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
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010158f48)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffff800010158f48-ffff800010158fec: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a6354)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
c03a6354-c03a63c0: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad4d0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
c0000000001ad4d0-c0000000001ad55c: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff0fa)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffe0000ff0fa-ffffffe0000ff184: wake_bit_function (STB_GLOBAL)
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
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eeea0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810eeea0-ffffffff810eeecc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810def20)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810def20-ffffffff810def4c: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ebfd0)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810ebfd0-ffffffff810ebffc: wake_bit_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wake_bit_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f7020)
Location: kernel/sched/wait_bit.c:21
Inline: False
```
**Symbols:**

```
ffffffff810f7020-ffffffff810f704c: wake_bit_function (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
</li>
</ul>
</details>
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
