# Function: <code>__elevator_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3680)
Location: block/elevator.c:950
Inline: False
Direct callers:
  - block/elevator.c:elevator_change
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff813b3680-ffffffff813b3826: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7380)
Location: block/elevator.c:949
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_change
```
**Symbols:**

```
ffffffff813f7380-ffffffff813f7525: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410d90)
Location: block/elevator.c:947
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_change
```
**Symbols:**

```
ffffffff81410d90-ffffffff81410f35: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f76e)
Location: block/elevator.c:1053
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8144a28e)
Location: block/elevator.c:1070
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147d36e)
Location: block/elevator.c:1081
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149ac43)
Location: block/elevator.c:658
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814c8d33)
Location: block/elevator.c:657
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814e1f13)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815409c0)
Location: block/elevator.c:730
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff815409c0-ffffffff81540bb2: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155d140)
Location: block/elevator.c:723
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff8155d140-ffffffff8155d332: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815659d0)
Location: block/elevator.c:724
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff815659d0-ffffffff81565bb8: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9da0)
Location: block/elevator.c:742
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff815c9da0-ffffffff815c9f88: __elevator_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __elevator_change(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81675150)
Location: block/elevator.c:746
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff81675150-ffffffff8167535c: __elevator_change (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105df190)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (c078c074)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (c0000000007711fc)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffe000421bf8)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814da4f3)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814caea3)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814d6583)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
In block/elevator.c (ffffffff814ef193)
Location: block/elevator.c:730
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
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
