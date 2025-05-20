# Function: <code>__dd_dispatch_request</code>

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
In block/mq-deadline.c (ffffffff814c84a4)
Location: block/mq-deadline.c:270
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff814f6da4)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81514bb1)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575c20)
Location: block/mq-deadline.c:271
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81575c20-ffffffff81575dcf: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81592a20)
Location: block/mq-deadline.c:271
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81592a20-ffffffff81592bcf: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81599840)
Location: block/mq-deadline.c:273
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81599840-ffffffff815999ef: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd, struct dd_per_prio *per_prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601c20)
Location: block/mq-deadline.c:362
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81601c20-ffffffff81601e72: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd, struct dd_per_prio *per_prio, long unsigned int latest_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b4870)
Location: block/mq-deadline.c:365
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff816b4870-ffffffff816b4b70: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd, struct dd_per_prio *per_prio, long unsigned int latest_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81774320)
Location: block/mq-deadline.c:423
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81774320-ffffffff81774620: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd, struct dd_per_prio *per_prio, long unsigned int latest_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817b3310)
Location: block/mq-deadline.c:443
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff817b3310-ffffffff817b36da: __dd_dispatch_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct request *__dd_dispatch_request(struct deadline_data *dd, struct dd_per_prio *per_prio, long unsigned int latest_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:443
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff817f7260-ffffffff817f75a4: __dd_dispatch_request (STB_LOCAL)
ffffffff821d44c6-ffffffff821d44db: __dd_dispatch_request.cold (STB_LOCAL)
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
In block/mq-deadline.c (ffff800010619be4)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (c07c4348)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (c0000000007b90dc)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffe00044f640)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff8150d191)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff814fd5c1)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81509221)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81522931)
Location: block/mq-deadline.c:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int latest_start</code>
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
