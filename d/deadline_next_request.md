# Function: <code>deadline_next_request</code>

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
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814ad9a0)
Location: block/deadline-iosched.c:279
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff814ad9a0-ffffffff814ada43: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c80f0)
Location: block/mq-deadline.c:236
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814c80f0-ffffffff814c81b9: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6990)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814f6990-ffffffff814f6a6d: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81514840)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81514840-ffffffff8151491d: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575db9)
Location: block/mq-deadline.c:237
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff815756e0-ffffffff81575799: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81592bb9)
Location: block/mq-deadline.c:237
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff815924d0-ffffffff81592596: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815999d9)
Location: block/mq-deadline.c:239
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff815991b0-ffffffff81599276: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:330
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81601780-ffffffff81601857: deadline_next_request (STB_LOCAL)
ffffffff81cd9f81-ffffffff81cd9f9e: deadline_next_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:319
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff816b4070-ffffffff816b417f: deadline_next_request (STB_LOCAL)
ffffffff81e8da6b-ffffffff81e8da88: deadline_next_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:371
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81773b00-ffffffff81773c7e: deadline_next_request (STB_LOCAL)
ffffffff82076fb1-ffffffff82076fce: deadline_next_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:390
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff817b3050-ffffffff817b32f9: deadline_next_request (STB_LOCAL)
ffffffff820f6ed9-ffffffff820f6f2b: deadline_next_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, struct dd_per_prio *per_prio, enum dd_data_dir data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:390
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff817f6be0-ffffffff817f6e8b: deadline_next_request (STB_LOCAL)
ffffffff821d42d4-ffffffff821d43ac: deadline_next_request.cold (STB_LOCAL)
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
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff800010619490)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffff800010619490-ffff800010619614: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c3fec)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c07c3fec-c07c4104: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8c80)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c0000000007b8c80-c0000000007b8de8: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044f1e8)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffe00044f1e8-ffffffe00044f328: deadline_next_request (STB_LOCAL)
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
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150ce20)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff8150ce20-ffffffff8150cefd: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fd250)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814fd250-ffffffff814fd32d: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81508eb0)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81508eb0-ffffffff81508f8d: deadline_next_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *deadline_next_request(struct deadline_data *dd, int data_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81522650)
Location: block/mq-deadline.c:237
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81522650-ffffffff8152272d: deadline_next_request (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dd_per_prio *per_prio</code>
</li>
<li>
<b>Param reordered. </b>
<code>dd, data_dir</code> ➡️ <code>dd, per_prio, data_dir</code>
</li>
<li>
<b>Param type changed. </b>
<code>int data_dir</code> ➡️ <code>enum dd_data_dir data_dir</code>
</li>
</ul>
</details>
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
