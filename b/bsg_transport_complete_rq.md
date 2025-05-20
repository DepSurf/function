# Function: <code>bsg_transport_complete_rq</code>

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
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814a6570)
Location: block/bsg-lib.c:56
Inline: False
```
**Symbols:**

```
ffffffff814a6570-ffffffff814a66cd: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c04a0)
Location: block/bsg-lib.c:61
Inline: False
```
**Symbols:**

```
ffffffff814c04a0-ffffffff814c05fd: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff814eec00-ffffffff814eed4c: bsg_transport_complete_rq (STB_LOCAL)
ffffffff814ef224-ffffffff814ef241: bsg_transport_complete_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81508060)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff81508060-ffffffff81508200: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81569250)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff81569250-ffffffff815693f0: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81583b20)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff81583b20-ffffffff81583cc0: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158a930)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff8158a930-ffffffff8158aab4: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060b190)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffff80001060b190-ffff80001060b440: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b5aa8)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
c07b5aa8-c07b5c78: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a7100)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
c0000000007a7100-c0000000007a7368: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443dba)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffe000443dba-ffffffe000443ee8: bsg_transport_complete_rq (STB_LOCAL)
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
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500640)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff81500640-ffffffff815007e0: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f0b50)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff814f0b50-ffffffff814f0cf0: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fc6d0)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff814fc6d0-ffffffff814fc870: bsg_transport_complete_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bsg_transport_complete_rq(struct request *rq, struct sg_io_v4 *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81515780)
Location: block/bsg-lib.c:76
Inline: False
```
**Symbols:**

```
ffffffff81515780-ffffffff81515920: bsg_transport_complete_rq (STB_LOCAL)
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
