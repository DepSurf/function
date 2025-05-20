# Function: <code>io_complete_rw</code>

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
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e390)
Location: fs/io_uring.c:885
Inline: False
```
**Symbols:**

```
ffffffff8132e390-ffffffff8132e3f2: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813418b0)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffff813418b0-ffffffff8134193d: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81382d80)
Location: fs/io_uring.c:2016
Inline: True
```
**Symbols:**

```
ffffffff81382d80-ffffffff81382da1: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397fa0)
Location: fs/io_uring.c:2754
Inline: False
```
**Symbols:**

```
ffffffff81397fa0-ffffffff81397fd5: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395e70)
Location: fs/io_uring.c:2517
Inline: False
```
**Symbols:**

```
ffffffff81395e70-ffffffff81395e82: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1330)
Location: fs/io_uring.c:2739
Inline: False
```
**Symbols:**

```
ffffffff813e1330-ffffffff813e13e7: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cc4a0)
Location: io_uring/io_uring.c:3265
Inline: True
```
**Symbols:**

```
ffffffff816cc4a0-ffffffff816cc52d: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3e30)
Location: io_uring/rw.c:298
Inline: True
```
**Symbols:**

```
ffffffff817a3e30-ffffffff817a3f08: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e4e90)
Location: io_uring/rw.c:298
Inline: True
```
**Symbols:**

```
ffffffff817e4e90-ffffffff817e4f68: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff818290c0)
Location: io_uring/rw.c:321
Inline: False
Direct callers:
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff818290c0-ffffffff8182914b: io_complete_rw (STB_LOCAL)
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
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401a48)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffff800010401a48-ffff800010401ad4: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d397c)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
c05d397c-c05d39ec: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050b730)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
c00000000050b730-c00000000050b7ec: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002adb8e)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffe0002adb8e-ffffffe0002adc2c: io_complete_rw (STB_LOCAL)
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
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339e90)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffff81339e90-ffffffff81339f1d: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132abc0)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffff8132abc0-ffffffff8132ac4d: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81337960)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffff81337960-ffffffff813379ed: io_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134ace0)
Location: fs/io_uring.c:953
Inline: False
```
**Symbols:**

```
ffffffff8134ace0-ffffffff8134ad6d: io_complete_rw (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int res2</code>
</li>
</ul>
</details>
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
