# Function: <code>kfifo_copy_to_user</code>

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
In lib/kfifo.c (ffffffff813fe910)
Location: lib/kfifo.c:249
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_to_user
  - lib/kfifo.c:__kfifo_to_user_r
```
**Symbols:**

```
ffffffff813fe910-ffffffff813fe9c1: kfifo_copy_to_user.isra.10 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81446370)
Location: lib/kfifo.c:249
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81446370-ffffffff8144646f: kfifo_copy_to_user.isra.10 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81464b60)
Location: lib/kfifo.c:249
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81464b60-ffffffff81464c5f: kfifo_copy_to_user.isra.10 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81469ba0)
Location: lib/kfifo.c:249
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81469ba0-ffffffff81469c9e: kfifo_copy_to_user.isra.8 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81495e70)
Location: lib/kfifo.c:249
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81495e70-ffffffff81495f6e: kfifo_copy_to_user.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814cb130)
Location: lib/kfifo.c:249
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff814cb130-ffffffff814cb22c: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814dfc40)
Location: lib/kfifo.c:249
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff814dfc40-ffffffff814dfd3c: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8150bd80)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff8150bd80-ffffffff8150be7c: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81529bb0)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81529bb0-ffffffff81529cd0: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8158d240)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff8158d240-ffffffff8158d368: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815a9c50)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff815a9c50-ffffffff815a9d78: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815b4aa0)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff815b4aa0-ffffffff815b4bc2: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8161a950)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff8161a950-ffffffff8161aa72: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff816e7d20)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff816e7d20-ffffffff816e7e48: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff817d7c00)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff817d7c00-ffffffff817d7d28: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81816e10)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81816e10-ffffffff81816f38: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8185c0f0)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff8185c0f0-ffffffff8185c218: kfifo_copy_to_user (STB_LOCAL)
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
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffff800010634880)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffff800010634880-ffff800010634c20: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c07da770)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
c07da770-c07da974: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c0000000007da090)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
c0000000007da090-c0000000007da284: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffe000462676)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffe000462676-ffffffe0004627a4: kfifo_copy_to_user (STB_LOCAL)
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
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81522190)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81522190-ffffffff815222b0: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81512480)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81512480-ffffffff815125a0: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8151e220)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff8151e220-ffffffff8151e340: kfifo_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo *fifo, void *to, unsigned int len, unsigned int off, unsigned int *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81537a90)
Location: lib/kfifo.c:236
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_to_user_r
  - lib/kfifo.c:__kfifo_to_user
```
**Symbols:**

```
ffffffff81537a90-ffffffff81537bb0: kfifo_copy_to_user (STB_LOCAL)
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
