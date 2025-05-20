# Function: <code>aio_poll_wake</code>

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
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81308f80)
Location: fs/aio.c:1663
Inline: False
```
**Symbols:**

```
ffffffff81308f80-ffffffff8130909d: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132ad70)
Location: fs/aio.c:1662
Inline: False
```
**Symbols:**

```
ffffffff8132ad70-ffffffff8132b0bc: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133be70)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffff8133be70-ffffffff8133bfff: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81378af0)
Location: fs/aio.c:1677
Inline: False
```
**Symbols:**

```
ffffffff81378af0-ffffffff81378d27: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81386820)
Location: fs/aio.c:1675
Inline: False
```
**Symbols:**

```
ffffffff81386820-ffffffff81386a63: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138c4d0)
Location: fs/aio.c:1672
Inline: False
```
**Symbols:**

```
ffffffff8138c4d0-ffffffff8138c715: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1732
Inline: False
```
**Symbols:**

```
ffffffff813d9a90-ffffffff813d9d46: aio_poll_wake (STB_LOCAL)
ffffffff81cc5730-ffffffff81cc5761: aio_poll_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1756
Inline: False
```
**Symbols:**

```
ffffffff81463f40-ffffffff814641f5: aio_poll_wake (STB_LOCAL)
ffffffff81e7812c-ffffffff81e78164: aio_poll_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1757
Inline: False
```
**Symbols:**

```
ffffffff814f4250-ffffffff814f4505: aio_poll_wake (STB_LOCAL)
ffffffff8206a062-ffffffff8206a09a: aio_poll_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1749
Inline: False
```
**Symbols:**

```
ffffffff8152b020-ffffffff8152b2db: aio_poll_wake (STB_LOCAL)
ffffffff820ea03b-ffffffff820ea073: aio_poll_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1792
Inline: False
```
**Symbols:**

```
ffffffff8155fef0-ffffffff815601ab: aio_poll_wake (STB_LOCAL)
ffffffff821c6ae0-ffffffff821c6b18: aio_poll_wake.cold (STB_LOCAL)
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
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fe7e0)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffff8000103fe7e0-ffff8000103fea50: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05d01d0)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
c05d01d0-c05d03f8: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000504350)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
c000000000504350-c000000000504884: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9f16)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffe0002a9f16-ffffffe0002aa0fc: aio_poll_wake (STB_LOCAL)
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
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81334450)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffff81334450-ffffffff813345df: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81327d50)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffff81327d50-ffffffff81328101: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331f20)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffff81331f20-ffffffff813320af: aio_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81347d60)
Location: fs/aio.c:1670
Inline: False
```
**Symbols:**

```
ffffffff81347d60-ffffffff81348186: aio_poll_wake (STB_LOCAL)
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
