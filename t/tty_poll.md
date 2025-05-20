# Function: <code>tty_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1820)
Location: drivers/tty/tty_io.c:2191
Inline: False
```
**Symbols:**

```
ffffffff814e1820-ffffffff814e18a5: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531160)
Location: drivers/tty/tty_io.c:2201
Inline: False
```
**Symbols:**

```
ffffffff81531160-ffffffff815311f3: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d8b0)
Location: drivers/tty/tty_io.c:2201
Inline: False
```
**Symbols:**

```
ffffffff8155d8b0-ffffffff8155d943: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815727c0)
Location: drivers/tty/tty_io.c:1959
Inline: False
```
**Symbols:**

```
ffffffff815727c0-ffffffff81572852: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d6b40)
Location: drivers/tty/tty_io.c:2066
Inline: False
```
**Symbols:**

```
ffffffff815d6b40-ffffffff815d6bd5: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160fb30)
Location: drivers/tty/tty_io.c:2084
Inline: False
```
**Symbols:**

```
ffffffff8160fb30-ffffffff8160fbc5: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c9f0)
Location: drivers/tty/tty_io.c:2096
Inline: False
```
**Symbols:**

```
ffffffff8162c9f0-ffffffff8162ca85: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660950)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81660950-ffffffff816609e5: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682fa0)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81682fa0-ffffffff81683035: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2099
Inline: False
```
**Symbols:**

```
ffffffff81735720-ffffffff817357b1: tty_poll (STB_LOCAL)
ffffffff817385ff-ffffffff81738653: tty_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2183
Inline: False
```
**Symbols:**

```
ffffffff817518f0-ffffffff81751981: tty_poll (STB_LOCAL)
ffffffff81c073a2-ffffffff81c073f6: tty_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2218
Inline: False
```
**Symbols:**

```
ffffffff81735780-ffffffff81735811: tty_poll (STB_LOCAL)
ffffffff81bf900c-ffffffff81bf9060: tty_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2214
Inline: False
```
**Symbols:**

```
ffffffff817b6140-ffffffff817b61d1: tty_poll (STB_LOCAL)
ffffffff81cf87a9-ffffffff81cf87fd: tty_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2199
Inline: False
```
**Symbols:**

```
ffffffff818f35b0-ffffffff818f365f: tty_poll (STB_LOCAL)
ffffffff81ec09c1-ffffffff81ec0a11: tty_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4a060)
Location: drivers/tty/tty_io.c:2194
Inline: False
```
**Symbols:**

```
ffffffff81a4a060-ffffffff81a4a123: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a94020)
Location: drivers/tty/tty_io.c:2203
Inline: False
```
**Symbols:**

```
ffffffff81a94020-ffffffff81a940e6: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae6a90)
Location: drivers/tty/tty_io.c:2201
Inline: False
```
**Symbols:**

```
ffffffff81ae6a90-ffffffff81ae6b56: tty_poll (STB_LOCAL)
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
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f0a8)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffff80001084f0a8-ffff80001084f164: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b414)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
c095b414-c095b4b0: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ee750)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
c0000000008ee750-c0000000008ee85c: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d810)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffe00052d810-ffffffe00052d896: tty_poll (STB_LOCAL)
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
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648a20)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81648a20-ffffffff81648ab5: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628e80)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81628e80-ffffffff81628f15: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676de0)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81676de0-ffffffff81676e75: tty_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t tty_poll(struct file *filp, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691500)
Location: drivers/tty/tty_io.c:2100
Inline: False
```
**Symbols:**

```
ffffffff81691500-ffffffff81691595: tty_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
