# Function: <code>aio_poll</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813097c8)
Location: fs/aio.c:1722
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132b1d4)
Location: fs/aio.c:1717
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133e024)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_poll(struct aio_kiocb *aiocb, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81377cf0)
Location: fs/aio.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81377cf0-ffffffff81377fbf: aio_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_poll(struct aio_kiocb *aiocb, const struct iocb *iocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813859e0)
Location: fs/aio.c:1738
Inline: False
```
**Symbols:**

```
ffffffff813859e0-ffffffff81385cbb: aio_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8138cb10)
Location: fs/aio.c:1735
Inline: True
```
**Symbols:**

```
ffffffff8138cb10-ffffffff8138ce06: aio_poll.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1839
Inline: True
```
**Symbols:**

```
ffffffff813da1f0-ffffffff813da57b: aio_poll.constprop.0 (STB_LOCAL)
ffffffff81cc578b-ffffffff81cc57c5: aio_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1863
Inline: True
```
**Symbols:**

```
ffffffff81464ba0-ffffffff81464f52: aio_poll.constprop.0 (STB_LOCAL)
ffffffff81e781b8-ffffffff81e781f2: aio_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1864
Inline: True
```
**Symbols:**

```
ffffffff814f4bc0-ffffffff814f4f72: aio_poll.constprop.0 (STB_LOCAL)
ffffffff8206a0ee-ffffffff8206a128: aio_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1856
Inline: True
```
**Symbols:**

```
ffffffff8152b990-ffffffff8152bd40: aio_poll.constprop.0 (STB_LOCAL)
ffffffff820ea0c7-ffffffff820ea101: aio_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1899
Inline: True
```
**Symbols:**

```
ffffffff81560870-ffffffff81560c20: aio_poll.constprop.0 (STB_LOCAL)
ffffffff821c6b6c-ffffffff821c6ba6: aio_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fdc00)
Location: fs/aio.c:1733
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cf224)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000507090)
Location: fs/aio.c:1733
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002ab49a)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81336604)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81326f84)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813340d4)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81344d54)
Location: fs/aio.c:1733
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
