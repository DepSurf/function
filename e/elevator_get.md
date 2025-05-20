# Function: <code>elevator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct elevator_type *elevator_get(const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3110)
Location: block/elevator.c:99
Inline: False
Direct callers:
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:__elevator_change
```
**Symbols:**

```
ffffffff813b3110-ffffffff813b31b6: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct elevator_type *elevator_get(const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f6e00)
Location: block/elevator.c:99
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff813f6e00-ffffffff813f6ea6: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct elevator_type *elevator_get(const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410810)
Location: block/elevator.c:99
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff81410810-ffffffff814108b6: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct elevator_type *elevator_get(const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e1d0)
Location: block/elevator.c:103
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff8141e1d0-ffffffff8141e273: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449020)
Location: block/elevator.c:116
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff81449020-ffffffff814490e6: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c420)
Location: block/elevator.c:116
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff8147c420-ffffffff8147c4e3: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8149a510)
Location: block/elevator.c:115
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8149a510-ffffffff8149a5b0: elevator_get.constprop.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814c85e0)
Location: block/elevator.c:116
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814c85e0-ffffffff814c8682: elevator_get.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e16f0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814e16f0-ffffffff814e17a5: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540210)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff81540210-ffffffff815402c5: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c9b0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8155c9b0-ffffffff8155ca65: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565240)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff81565240-ffffffff815652fa: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c95e0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff815c95e0-ffffffff815c969a: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff816747c0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff816747c0-ffffffff81674881: elevator_get (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffff8000105de6d8)
Location: block/elevator.c:140
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffff8000105de6d8-ffff8000105de844: elevator_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b664)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
c078b664-c078b740: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c0000000007701b0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
c0000000007701b0-c00000000077032c: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe00042133a)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffe00042133a-ffffffe000421470: elevator_get (STB_LOCAL)
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
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9cd0)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814d9cd0-ffffffff814d9d85: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca680)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814ca680-ffffffff814ca735: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5d60)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814d5d60-ffffffff814d5e15: elevator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct elevator_type *elevator_get(struct request_queue *q, const char *name, bool try_loading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee810)
Location: block/elevator.c:140
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814ee810-ffffffff814ee8c2: elevator_get (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, try_loading</code> ➡️ <code>q, name, try_loading</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
</ul>
<b>Arch</b>
<ul>
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
