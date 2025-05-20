# Function: <code>aio_poll_cancel</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307700)
Location: fs/aio.c:1647
Inline: False
```
**Symbols:**

```
ffffffff81307700-ffffffff81307763: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328d00)
Location: fs/aio.c:1646
Inline: False
```
**Symbols:**

```
ffffffff81328d00-ffffffff81328d63: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133bb00)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffff8133bb00-ffffffff8133bb63: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375de0)
Location: fs/aio.c:1661
Inline: False
```
**Symbols:**

```
ffffffff81375de0-ffffffff81375e46: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383cb0)
Location: fs/aio.c:1659
Inline: False
```
**Symbols:**

```
ffffffff81383cb0-ffffffff81383d16: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138b3b0)
Location: fs/aio.c:1656
Inline: False
```
**Symbols:**

```
ffffffff8138b3b0-ffffffff8138b416: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1715
Inline: False
```
**Symbols:**

```
ffffffff813da160-ffffffff813da1ef: aio_poll_cancel (STB_LOCAL)
ffffffff81cc5776-ffffffff81cc578b: aio_poll_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff814616d2)
Location: fs/aio.c:1739
Inline: True
```
**Symbols:**

```
ffffffff814616a0-ffffffff81461744: aio_poll_cancel (STB_LOCAL)
ffffffff81e78117-ffffffff81e7812c: aio_poll_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff814f16a2)
Location: fs/aio.c:1740
Inline: True
```
**Symbols:**

```
ffffffff814f1670-ffffffff814f1714: aio_poll_cancel (STB_LOCAL)
ffffffff8206a04d-ffffffff8206a062: aio_poll_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81528c42)
Location: fs/aio.c:1732
Inline: True
```
**Symbols:**

```
ffffffff81528c10-ffffffff81528cb4: aio_poll_cancel (STB_LOCAL)
ffffffff820ea026-ffffffff820ea03b: aio_poll_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8155dd42)
Location: fs/aio.c:1775
Inline: True
```
**Symbols:**

```
ffffffff8155dd10-ffffffff8155ddb4: aio_poll_cancel (STB_LOCAL)
ffffffff821c6acb-ffffffff821c6ae0: aio_poll_cancel.cold (STB_LOCAL)
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
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa788)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffff8000103fa788-ffff8000103fa844: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05ce410)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
c05ce410-c05ce49c: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000502ee0)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
c000000000502ee0-c000000000502fdc: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aa1e2)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffe0002aa1e2-ffffffe0002aa282: aio_poll_cancel (STB_LOCAL)
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
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813340e0)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffff813340e0-ffffffff81334143: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324c00)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffff81324c00-ffffffff81324c63: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331bb0)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffff81331bb0-ffffffff81331c13: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_poll_cancel(struct kiocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81343af0)
Location: fs/aio.c:1654
Inline: False
```
**Symbols:**

```
ffffffff81343af0-ffffffff81343b51: aio_poll_cancel (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
