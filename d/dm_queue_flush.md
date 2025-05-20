# Function: <code>dm_queue_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a0970)
Location: drivers/md/dm.c:2992
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff816a0970-ffffffff816a099b: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701cc0)
Location: drivers/md/dm.c:1995
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81701cc0-ffffffff81701ceb: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733b10)
Location: drivers/md/dm.c:2050
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81733b10-ffffffff81733b3b: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174cc50)
Location: drivers/md/dm.c:2260
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8174cc50-ffffffff8174cc7b: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bee30)
Location: drivers/md/dm.c:2234
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff817bee30-ffffffff817bee58: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818073c0)
Location: drivers/md/dm.c:2423
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818073c0-ffffffff818073e8: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818333f0)
Location: drivers/md/dm.c:2449
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818333f0-ffffffff81833418: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875320)
Location: drivers/md/dm.c:2480
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81875320-ffffffff81875348: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a70d0)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818a70d0-ffffffff818a70f8: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977a6c)
Location: drivers/md/dm.c:2525
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197c6fc)
Location: drivers/md/dm.c:2381
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819602cc)
Location: drivers/md/dm.c:2400
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0858c)
Location: drivers/md/dm.c:2289
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b71a57)
Location: drivers/md/dm.c:2470
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0ec87)
Location: drivers/md/dm.c:2573
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d78267)
Location: drivers/md/dm.c:2609
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2f497)
Location: drivers/md/dm.c:2617
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
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
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afcc50)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffff800010afcc50-ffff800010afccc8: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdc9b4)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c0bdc9b4-c0bdc9f0: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bea9b0)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c000000000bea9b0-c000000000beaa0c: dm_queue_flush (STB_LOCAL)
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
In drivers/md/dm.c (ffffffe0006ed69c)
Location: drivers/md/dm.c:2485
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
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
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184cf50)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8184cf50-ffffffff8184cf78: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814570)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81814570-ffffffff81814598: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189c580)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8189c580-ffffffff8189c5a8: dm_queue_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dm_queue_flush(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b87c0)
Location: drivers/md/dm.c:2485
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818b87c0-ffffffff818b87e8: dm_queue_flush (STB_LOCAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
