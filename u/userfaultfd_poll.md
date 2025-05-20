# Function: <code>userfaultfd_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81259e80)
Location: fs/userfaultfd.c:505
Inline: True
```
**Symbols:**

```
ffffffff81259e80-ffffffff81259ee7: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81282890)
Location: fs/userfaultfd.c:509
Inline: True
```
**Symbols:**

```
ffffffff81282890-ffffffff812828fa: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812963b0)
Location: fs/userfaultfd.c:544
Inline: True
```
**Symbols:**

```
ffffffff812963b0-ffffffff8129641a: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a3230)
Location: fs/userfaultfd.c:896
Inline: True
```
**Symbols:**

```
ffffffff812a3230-ffffffff812a32b2: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c65c0)
Location: fs/userfaultfd.c:940
Inline: True
```
**Symbols:**

```
ffffffff812c65c0-ffffffff812c6648: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812ef6f0)
Location: fs/userfaultfd.c:955
Inline: True
```
**Symbols:**

```
ffffffff812ef6f0-ffffffff812ef777: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813040a0)
Location: fs/userfaultfd.c:960
Inline: True
```
**Symbols:**

```
ffffffff813040a0-ffffffff8130412c: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81325630)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff81325630-ffffffff813256be: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813383c0)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff813383c0-ffffffff8133844e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81371fb0)
Location: fs/userfaultfd.c:975
Inline: False
```
**Symbols:**

```
ffffffff81371fb0-ffffffff8137203e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8137fdf0)
Location: fs/userfaultfd.c:939
Inline: False
```
**Symbols:**

```
ffffffff8137fdf0-ffffffff8137fe7e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81386aa0)
Location: fs/userfaultfd.c:939
Inline: False
```
**Symbols:**

```
ffffffff81386aa0-ffffffff81386b2e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d3d30)
Location: fs/userfaultfd.c:940
Inline: False
```
**Symbols:**

```
ffffffff813d3d30-ffffffff813d3dac: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145d2f0)
Location: fs/userfaultfd.c:949
Inline: False
```
**Symbols:**

```
ffffffff8145d2f0-ffffffff8145d384: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ecbf0)
Location: fs/userfaultfd.c:969
Inline: False
```
**Symbols:**

```
ffffffff814ecbf0-ffffffff814ecc84: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81523890)
Location: fs/userfaultfd.c:998
Inline: False
```
**Symbols:**

```
ffffffff81523890-ffffffff81523924: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81557eb0)
Location: fs/userfaultfd.c:991
Inline: False
```
**Symbols:**

```
ffffffff81557eb0-ffffffff81557f44: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f6b38)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffff8000103f6b38-ffff8000103f6bfc: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cb228)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
c05cb228-c05cb2f8: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c0000000004febb0)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
c0000000004febb0-c0000000004fecb8: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a6e0a)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffe0002a6e0a-ffffffe0002a6ea4: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813309a0)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff813309a0-ffffffff81330a2e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81321590)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff81321590-ffffffff8132161e: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8132e470)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff8132e470-ffffffff8132e4fe: userfaultfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__poll_t userfaultfd_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81340ea0)
Location: fs/userfaultfd.c:976
Inline: True
```
**Symbols:**

```
ffffffff81340ea0-ffffffff81340f2e: userfaultfd_poll (STB_LOCAL)
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
