# Function: <code>io_uring_create</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81330e30)
Location: fs/io_uring.c:3324
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81330e30-ffffffff81331599: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81344a20)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81344a20-ffffffff813451d1: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813856f0)
Location: fs/io_uring.c:8154
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff813856f0-ffffffff81385b58: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396720)
Location: fs/io_uring.c:9650
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81396720-ffffffff81396e2b: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399bb0)
Location: fs/io_uring.c:9624
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81399bb0-ffffffff8139a09d: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:10297
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff813e8c70-ffffffff813e91a1: io_uring_create (STB_LOCAL)
ffffffff81cc5be6-ffffffff81cc5c24: io_uring_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e924f4)
Location: io_uring/io_uring.c:11955
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81e924f4-ffffffff81e928ab: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3529
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff8178ca80-ffffffff8178cf9c: io_uring_create (STB_LOCAL)
ffffffff82077573-ffffffff820775b3: io_uring_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3817
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff817cdb90-ffffffff817ce0d5: io_uring_create (STB_LOCAL)
ffffffff820f75b2-ffffffff820f75f7: io_uring_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3822
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff81816760-ffffffff81816c5a: io_uring_create (STB_LOCAL)
ffffffff821d50e8-ffffffff821d512d: io_uring_create.cold (STB_LOCAL)
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
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010402e58)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffff800010402e58-ffff8000104034f4: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d62ec)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
c05d62ec-c05d6a8c: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050f780)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
c00000000050f780-c00000000050ff74: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002b0608)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffe0002b0608-ffffffe0002b0c4a: io_uring_create (STB_LOCAL)
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
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133d000)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff8133d000-ffffffff8133d7b1: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132dcc0)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff8132dcc0-ffffffff8132e471: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133aad0)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff8133aad0-ffffffff8133b281: io_uring_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_uring_create(unsigned int entries, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134dc80)
Location: fs/io_uring.c:3882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_setup
```
**Symbols:**

```
ffffffff8134dc80-ffffffff8134e431: io_uring_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_uring_params *params</code>
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
