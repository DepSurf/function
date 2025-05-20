# Function: <code>deadline_fifo_request</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814adbb0)
Location: block/deadline-iosched.c:248
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff814adbb0-ffffffff814adc7a: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c8280)
Location: block/mq-deadline.c:200
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814c8280-ffffffff814c8375: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6b30)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814f6b30-ffffffff814f6c39: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815149e0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff815149e0-ffffffff81514ae9: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575820)
Location: block/mq-deadline.c:201
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81575820-ffffffff81575911: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81592620)
Location: block/mq-deadline.c:201
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81592620-ffffffff8159271b: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81599440)
Location: block/mq-deadline.c:203
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81599440-ffffffff8159953d: deadline_fifo_request (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff81601d05)
Location: block/mq-deadline.c:296
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81601860-ffffffff8160191e: deadline_fifo_request.part.0 (STB_LOCAL)
ffffffff81cd9f9e-ffffffff81cd9fc0: deadline_fifo_request.part.0.cold (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff816b49a5)
Location: block/mq-deadline.c:285
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff816b42f0-ffffffff816b43b7: deadline_fifo_request.part.0 (STB_LOCAL)
ffffffff81e8da88-ffffffff81e8daaa: deadline_fifo_request.part.0.cold (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff81774455)
Location: block/mq-deadline.c:332
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81773c90-ffffffff81773dad: deadline_fifo_request.part.0 (STB_LOCAL)
ffffffff82076fce-ffffffff82076ff3: deadline_fifo_request.part.0.cold (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff817b3470)
Location: block/mq-deadline.c:346
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff817b2db0-ffffffff817b303d: deadline_fifo_request.part.0 (STB_LOCAL)
ffffffff820f6e72-ffffffff820f6ed9: deadline_fifo_request.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (ffffffff817f73bb)
Location: block/mq-deadline.c:346
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff817f6ea0-ffffffff817f7143: deadline_fifo_request.part.0 (STB_LOCAL)
ffffffff821d43ac-ffffffff821d44a9: deadline_fifo_request.part.0.cold (STB_LOCAL)
ffffffff817f7160-ffffffff817f724e: deadline_fifo_request (STB_LOCAL)
ffffffff821d44a9-ffffffff821d44c6: deadline_fifo_request.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff8000106199e0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffff8000106199e0-ffff800010619b98: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c41e8)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c07c41e8-c07c4320: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8ef0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c0000000007b8ef0-c0000000007b9098: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044f3f2)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffe00044f3f2-ffffffe00044f54a: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150cfc0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff8150cfc0-ffffffff8150d0c9: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fd3f0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814fd3f0-ffffffff814fd4f9: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81509050)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81509050-ffffffff81509159: deadline_fifo_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_fifo_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815227f0)
Location: block/mq-deadline.c:201
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff815227f0-ffffffff815228f9: deadline_fifo_request (STB_LOCAL)
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
