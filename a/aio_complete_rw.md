# Function: <code>aio_complete_rw</code>

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
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f41d0)
Location: fs/aio.c:1389
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812f41d0-ffffffff812f4294: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81308e70)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81308e70-ffffffff81308f45: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813296d0)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff813296d0-ffffffff81329a09: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133d600)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff8133d600-ffffffff8133d939: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81377360)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81377360-ffffffff813774db: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81385650)
Location: fs/aio.c:1423
Inline: False
```
**Symbols:**

```
ffffffff81385650-ffffffff81385806: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138c8c0)
Location: fs/aio.c:1420
Inline: False
```
**Symbols:**

```
ffffffff8138c8c0-ffffffff8138ca76: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d9f10)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff813d9f10-ffffffff813da0c6: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81464400)
Location: fs/aio.c:1447
Inline: False
```
**Symbols:**

```
ffffffff81464400-ffffffff814645eb: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f4740)
Location: fs/aio.c:1448
Inline: False
```
**Symbols:**

```
ffffffff814f4740-ffffffff814f492b: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8152b510)
Location: fs/aio.c:1440
Inline: False
```
**Symbols:**

```
ffffffff8152b510-ffffffff8152b6fe: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815603e0)
Location: fs/aio.c:1497
Inline: False
```
**Symbols:**

```
ffffffff815603e0-ffffffff815605d6: aio_complete_rw (STB_LOCAL)
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
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fd300)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffff8000103fd300-ffff8000103fd4e4: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cfe50)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
c05cfe50-c05cffc8: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000506140)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
c000000000506140-c00000000050658c: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aacf4)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffe0002aacf4-ffffffe0002aae34: aio_complete_rw (STB_LOCAL)
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
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81335be0)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81335be0-ffffffff81335f19: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81326570)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81326570-ffffffff813268a9: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813336b0)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff813336b0-ffffffff813339e9: aio_complete_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aio_complete_rw(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813479c0)
Location: fs/aio.c:1421
Inline: False
```
**Symbols:**

```
ffffffff813479c0-ffffffff81347d53: aio_complete_rw (STB_LOCAL)
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
