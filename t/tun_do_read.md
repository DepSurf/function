# Function: <code>tun_do_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ee200)
Location: drivers/net/tun.c:1399
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff815ee200-ffffffff815ee5f0: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8164ed2e)
Location: drivers/net/tun.c:1483
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff8164e710-ffffffff8164ecd6: tun_do_read.part.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81680a41)
Location: drivers/net/tun.c:1474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81680420-ffffffff816809e4: tun_do_read.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81695eae)
Location: drivers/net/tun.c:1511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81695870-ffffffff81695e5c: tun_do_read.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81700a6a)
Location: drivers/net/tun.c:1958
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff817003c0-ffffffff817009a0: tun_do_read.part.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173fc20)
Location: drivers/net/tun.c:2186
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff8173fc20-ffffffff817402d4: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81763c40)
Location: drivers/net/tun.c:2204
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81763c40-ffffffff81764307: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2199
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff817a19e0-ffffffff817a205e: tun_do_read (STB_LOCAL)
ffffffff817a2f3b-ffffffff817a2f97: tun_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff817c26b0-ffffffff817c2d2e: tun_do_read (STB_LOCAL)
ffffffff817c699e-ffffffff817c69fa: tun_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188ead0)
Location: drivers/net/tun.c:2178
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff8188ead0-ffffffff8188eefe: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189cc40)
Location: drivers/net/tun.c:2100
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff8189cc40-ffffffff8189ce04: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187f2c0)
Location: drivers/net/tun.c:2105
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff8187f2c0-ffffffff8187f484: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81910e90)
Location: drivers/net/tun.c:2161
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81910e90-ffffffff819112dd: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a63f60)
Location: drivers/net/tun.c:2193
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81a63f60-ffffffff81a64150: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bef1a0)
Location: drivers/net/tun.c:2197
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81bef1a0-ffffffff81bef390: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c47280)
Location: drivers/net/tun.c:2211
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81c47280-ffffffff81c47470: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfcb80)
Location: drivers/net/tun.c:2223
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81cfcb80-ffffffff81cfcd70: tun_do_read (STB_LOCAL)
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
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dd1c8)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffff8000109dd1c8-ffff8000109dd86c: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac5908)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
c0ac5908-c0ac6068: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa37f0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
c000000000aa37f0-c000000000aa4174: tun_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000628444)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffe000628444-ffffffe0006289fc: tun_do_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81787180-ffffffff817877fe: tun_do_read (STB_LOCAL)
ffffffff8178b47e-ffffffff8178b4da: tun_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff81766ad0-ffffffff8176714e: tun_do_read (STB_LOCAL)
ffffffff8176adce-ffffffff8176ae2a: tun_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff817b7530-ffffffff817b7bae: tun_do_read (STB_LOCAL)
ffffffff817bb81e-ffffffff817bb87a: tun_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tun_do_read(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *to, int noblock, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2203
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
```
**Symbols:**

```
ffffffff817d1b90-ffffffff817d2283: tun_do_read (STB_LOCAL)
ffffffff817d5a6e-ffffffff817d5acb: tun_do_read.cold (STB_LOCAL)
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
