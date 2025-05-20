# Function: <code>__elevator_exit</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8690)
Location: block/elevator.c:181
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814c8690-ffffffff814c86dd: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e17b0)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814e17b0-ffffffff814e17fd: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540888)
Location: block/elevator.c:191
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff815402d0-ffffffff8154031d: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155d024)
Location: block/elevator.c:191
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff8155ca70-ffffffff8155cab3: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815658b4)
Location: block/elevator.c:191
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff81565300-ffffffff81565343: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9c94)
Location: block/elevator.c:191
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff815c96a0-ffffffff815c96e3: __elevator_exit (STB_GLOBAL)
```
</details>
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
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de848)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffff8000105de848-ffff8000105de8ac: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b80c)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c078b80c-c078b864: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770560)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c000000000770560-c0000000007705f4: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421470)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffe000421470-ffffffe0004214d0: __elevator_exit (STB_GLOBAL)
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
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9d90)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814d9d90-ffffffff814d9ddd: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca740)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814ca740-ffffffff814ca78d: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5e20)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814d5e20-ffffffff814d5e6d: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eea20)
Location: block/elevator.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814eea20-ffffffff814eea6d: __elevator_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
