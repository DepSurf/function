# Function: <code>put_reqs_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125b9a0)
Location: fs/aio.c:884
Inline: False
Direct callers:
  - fs/aio.c:refill_reqs_available
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff8125b9a0-ffffffff8125ba0c: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81284290)
Location: fs/aio.c:894
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81284290-ffffffff812842fc: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297f50)
Location: fs/aio.c:897
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81297f50-ffffffff81297fbc: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a6940)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff812a6940-ffffffff812a69ac: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c97e0)
Location: fs/aio.c:926
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff812c97e0-ffffffff812c984c: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f2940)
Location: fs/aio.c:889
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff812f2940-ffffffff812f29ac: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813075c0)
Location: fs/aio.c:905
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff813075c0-ffffffff8130762c: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328bb0)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81328bb0-ffffffff81328c1f: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b960)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff8133b960-ffffffff8133b9cf: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375600)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81375600-ffffffff8137566e: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813834e0)
Location: fs/aio.c:904
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff813834e0-ffffffff81383542: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138c250)
Location: fs/aio.c:901
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff8138c250-ffffffff8138c2bf: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d9810)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff813d9810-ffffffff813d987f: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81460970)
Location: fs/aio.c:928
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81460970-ffffffff814609ee: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f08b0)
Location: fs/aio.c:932
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff814f08b0-ffffffff814f0933: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81527650)
Location: fs/aio.c:930
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81527650-ffffffff815276d3: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155c490)
Location: fs/aio.c:940
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff8155c490-ffffffff8155c513: put_reqs_available (STB_LOCAL)
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
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103faa18)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffff8000103faa18-ffff8000103faab8: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cde74)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
c05cde74-c05cdef4: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000502d10)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
c000000000502d10-c000000000502db8: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9032)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffe0002a9032-ffffffe0002a90ae: put_reqs_available (STB_LOCAL)
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
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333f40)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81333f40-ffffffff81333faf: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81323dd0)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81323dd0-ffffffff81323e29: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331a10)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81331a10-ffffffff81331a7f: put_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_reqs_available(struct kioctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81344830)
Location: fs/aio.c:902
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:refill_reqs_available
```
**Symbols:**

```
ffffffff81344830-ffffffff8134489f: put_reqs_available (STB_LOCAL)
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
