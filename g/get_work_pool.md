# Function: <code>get_work_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81097a80)
Location: kernel/workqueue.c:685
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:flush_work
```
**Symbols:**

```
ffffffff81097a80-ffffffff81097adb: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b160)
Location: kernel/workqueue.c:705
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8109b160-ffffffff8109b1b7: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ff40)
Location: kernel/workqueue.c:707
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8109ff40-ffffffff8109ff97: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d330)
Location: kernel/workqueue.c:707
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8109d330-ffffffff8109d369: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3a70)
Location: kernel/workqueue.c:709
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810a3a70-ffffffff810a3aa9: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa560)
Location: kernel/workqueue.c:707
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810aa560-ffffffff810aa599: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b3630)
Location: kernel/workqueue.c:707
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b3630-ffffffff810b3669: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b91f0)
Location: kernel/workqueue.c:710
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b91f0-ffffffff810b9229: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf730)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810bf730-ffffffff810bf769: get_work_pool (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c7a08)
Location: kernel/workqueue.c:706
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff810c29e8)
Location: kernel/workqueue.c:706
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff810c47f8)
Location: kernel/workqueue.c:707
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff810d7418)
Location: kernel/workqueue.c:724
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff810f0afd)
Location: kernel/workqueue.c:726
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff811127ad)
Location: kernel/workqueue.c:726
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff8111edad)
Location: kernel/workqueue.c:773
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
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
In kernel/workqueue.c (ffffffff8112994d)
Location: kernel/workqueue.c:770
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:try_to_grab_pending
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
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011c1b0)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffff80001011c1b0-ffff80001011c224: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0370f8c)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
c0370f8c-c0370fd4: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001649c0)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
**Symbols:**

```
c0000000001649c0-c000000000164a38: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6676)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffe0000d6676-ffffffe0000d66da: get_work_pool (STB_LOCAL)
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
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9aa0)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b9aa0-ffffffff810b9ad9: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a83e0)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810a83e0-ffffffff810a8419: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9000)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b9000-ffffffff810b9039: get_work_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct worker_pool *get_work_pool(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1a60)
Location: kernel/workqueue.c:711
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c1a60-ffffffff810c1a99: get_work_pool (STB_LOCAL)
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
