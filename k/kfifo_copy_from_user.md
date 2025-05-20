# Function: <code>kfifo_copy_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff813fe6f0)
Location: lib/kfifo.c:188
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_from_user
  - lib/kfifo.c:__kfifo_from_user_r
```
**Symbols:**

```
ffffffff813fe6f0-ffffffff813fe7a1: kfifo_copy_from_user.isra.9 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81446120)
Location: lib/kfifo.c:188
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81446120-ffffffff81446219: kfifo_copy_from_user.isra.9 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81464910)
Location: lib/kfifo.c:188
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81464910-ffffffff81464a09: kfifo_copy_from_user.isra.9 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81469950)
Location: lib/kfifo.c:188
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81469950-ffffffff81469a48: kfifo_copy_from_user.isra.7 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81495c20)
Location: lib/kfifo.c:188
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81495c20-ffffffff81495d18: kfifo_copy_from_user.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814caf10)
Location: lib/kfifo.c:188
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff814caf10-ffffffff814cb006: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814dfe30)
Location: lib/kfifo.c:188
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff814dfe30-ffffffff814dff26: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8150bb50)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff8150bb50-ffffffff8150bc46: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81529970)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81529970-ffffffff81529a7b: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8158d480)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff8158d480-ffffffff8158d593: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815a9e90)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff815a9e90-ffffffff815a9fa3: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815b4860)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff815b4860-ffffffff815b4970: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8161a7d0)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff8161a7d0-ffffffff8161a8e0: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff816e7f80)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff816e7f80-ffffffff816e80a2: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff817d7e90)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff817d7e90-ffffffff817d7fb2: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff818170a0)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff818170a0-ffffffff818171c2: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8185c380)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff8185c380-ffffffff8185c4a2: kfifo_copy_from_user (STB_LOCAL)
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
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffff8000106345d8)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffff8000106345d8-ffff800010634708: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c07daa80)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
c07daa80-c07dacc0: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c0000000007d9c60)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
c0000000007d9c60-c0000000007d9e54: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffe000462400)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffe000462400-ffffffe00046252e: kfifo_copy_from_user (STB_LOCAL)
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
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81521f50)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81521f50-ffffffff8152205b: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81512240)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81512240-ffffffff8151234b: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8151dfe0)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff8151dfe0-ffffffff8151e0eb: kfifo_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo *fifo, const void *from, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81537850)
Location: lib/kfifo.c:175
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_from_user_r
  - lib/kfifo.c:__kfifo_from_user
```
**Symbols:**

```
ffffffff81537850-ffffffff8153795b: kfifo_copy_from_user (STB_LOCAL)
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
