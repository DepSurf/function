# Function: <code>tun_get_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815eec90)
Location: drivers/net/tun.c:1082
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff815eec90-ffffffff815ef511: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164d880)
Location: drivers/net/tun.c:1165
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8164d880-ffffffff8164e088: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167f5a0)
Location: drivers/net/tun.c:1156
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8167f5a0-ffffffff8167fd99: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816947d0)
Location: drivers/net/tun.c:1194
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff816947d0-ffffffff81695176: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fe840)
Location: drivers/net/tun.c:1552
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff816fe840-ffffffff816ffc5d: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173e510)
Location: drivers/net/tun.c:1738
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8173e510-ffffffff8173f69f: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817623c0)
Location: drivers/net/tun.c:1748
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817623c0-ffffffff81763484: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817a0100-ffffffff817a11bf: tun_get_user (STB_LOCAL)
ffffffff817a2f28-ffffffff817a2f3b: tun_get_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c50b0)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817c50b0-ffffffff817c6180: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188d7f0)
Location: drivers/net/tun.c:1710
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8188d7f0-ffffffff8188e2c2: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189bd30)
Location: drivers/net/tun.c:1641
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8189bd30-ffffffff8189c82c: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187e2b0)
Location: drivers/net/tun.c:1648
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8187e2b0-ffffffff8187ed91: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1704
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff8190faa0-ffffffff8191059e: tun_get_user (STB_LOCAL)
ffffffff81d10a94-ffffffff81d10ac3: tun_get_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1732
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff81a666f0-ffffffff81a675c5: tun_get_user (STB_LOCAL)
ffffffff81edba5a-ffffffff81edba90: tun_get_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1735
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff81bf1bc0-ffffffff81bf2a00: tun_get_user (STB_LOCAL)
ffffffff8209d779-ffffffff8209d7af: tun_get_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1741
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff81c4a830-ffffffff81c4b701: tun_get_user (STB_LOCAL)
ffffffff8211e6a0-ffffffff8211e6ca: tun_get_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1750
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff81d001b0-ffffffff81d00d9b: tun_get_user (STB_LOCAL)
ffffffff821ffcf3-ffffffff821ffd1c: tun_get_user.cold (STB_LOCAL)
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
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109e03b0)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffff8000109e03b0-ffff8000109e1294: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac44bc)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
c0ac44bc-c0ac585c: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa1360)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
c000000000aa1360-c000000000aa26a0: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000629fc2)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffe000629fc2-ffffffe00062ae22: tun_get_user (STB_LOCAL)
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
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81789b90)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff81789b90-ffffffff8178ac60: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817694e0)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817694e0-ffffffff8176a5b0: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b9f30)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817b9f30-ffffffff817bb000: tun_get_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t tun_get_user(struct tun_struct *tun, struct tun_file *tfile, void *msg_control, struct iov_iter *from, int noblock, bool more);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d2430)
Location: drivers/net/tun.c:1742
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
```
**Symbols:**

```
ffffffff817d2430-ffffffff817d355c: tun_get_user (STB_LOCAL)
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
<code>bool more</code>
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
