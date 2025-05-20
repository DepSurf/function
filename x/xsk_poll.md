# Function: <code>xsk_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cbad0)
Location: net/xdp/xsk.c:297
Inline: False
```
**Symbols:**

```
ffffffff819cbad0-ffffffff819cbb54: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04d20)
Location: net/xdp/xsk.c:309
Inline: False
```
**Symbols:**

```
ffffffff81a04d20-ffffffff81a04da4: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74200)
Location: net/xdp/xsk.c:316
Inline: False
```
**Symbols:**

```
ffffffff81a74200-ffffffff81a74284: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaae60)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffff81aaae60-ffffffff81aaaf4b: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7bb0)
Location: net/xdp/xsk.c:424
Inline: False
```
**Symbols:**

```
ffffffff81ba7bb0-ffffffff81ba7c72: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb77c0)
Location: net/xdp/xsk.c:594
Inline: False
```
**Symbols:**

```
ffffffff81bb77c0-ffffffff81bb78b1: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6940)
Location: net/xdp/xsk.c:687
Inline: False
```
**Symbols:**

```
ffffffff81ba6940-ffffffff81ba6a31: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:687
Inline: False
```
**Symbols:**

```
ffffffff81c74940-ffffffff81c74a4f: xsk_poll (STB_LOCAL)
ffffffff81d430d7-ffffffff81d430ec: xsk_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:702
Inline: False
```
**Symbols:**

```
ffffffff81e18490-ffffffff81e185c1: xsk_poll (STB_LOCAL)
ffffffff81f0fa7a-ffffffff81f0fa8f: xsk_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:713
Inline: False
```
**Symbols:**

```
ffffffff81fef7f0-ffffffff81fef969: xsk_poll (STB_LOCAL)
ffffffff820b5e3a-ffffffff820b5e4f: xsk_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:714
Inline: False
```
**Symbols:**

```
ffffffff8206b7b0-ffffffff8206b929: xsk_poll (STB_LOCAL)
ffffffff8213736e-ffffffff82137383: xsk_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
__poll_t xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:987
Inline: False
```
**Symbols:**

```
ffffffff8213f540-ffffffff8213f6d4: xsk_poll (STB_LOCAL)
ffffffff82219219-ffffffff8221922e: xsk_poll.cold (STB_LOCAL)
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
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e4b0)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffff800010d7e4b0-ffff800010d7e5dc: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e79a28)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
c0e79a28-c0e79b24: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebef10)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
c000000000ebef10-c000000000ebf07c: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ac7fe)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffe0008ac7fe-ffffffe0008ac8da: xsk_poll (STB_LOCAL)
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
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4a1f0)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffff81a4a1f0-ffffffff81a4a2db: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06de0)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffff81a06de0-ffffffff81a06ecb: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab60a0)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffff81ab60a0-ffffffff81ab618b: xsk_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int xsk_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac3090)
Location: net/xdp/xsk.c:430
Inline: False
```
**Symbols:**

```
ffffffff81ac3090-ffffffff81ac3158: xsk_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
