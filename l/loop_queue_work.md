# Function: <code>loop_queue_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81570640)
Location: drivers/block/loop.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81570640-ffffffff8157150a: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c61d0)
Location: drivers/block/loop.c:1739
Inline: False
```
**Symbols:**

```
ffffffff815c61d0-ffffffff815c6ce5: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f4740)
Location: drivers/block/loop.c:1710
Inline: False
```
**Symbols:**

```
ffffffff815f4740-ffffffff815f51f5: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816089e0)
Location: drivers/block/loop.c:1758
Inline: False
```
**Symbols:**

```
ffffffff816089e0-ffffffff8160942f: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81671280)
Location: drivers/block/loop.c:1786
Inline: False
```
**Symbols:**

```
ffffffff81671280-ffffffff81671cf8: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1849
Inline: False
```
**Symbols:**

```
ffffffff816acde0-ffffffff816ad779: loop_queue_work (STB_LOCAL)
ffffffff816ad7b2-ffffffff816ad7fd: loop_queue_work.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1939
Inline: False
```
**Symbols:**

```
ffffffff816cd130-ffffffff816cdacc: loop_queue_work (STB_LOCAL)
ffffffff816ce65f-ffffffff816ce6aa: loop_queue_work.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1990
Inline: False
```
**Symbols:**

```
ffffffff81709260-ffffffff81709d18: loop_queue_work (STB_LOCAL)
ffffffff81709dc5-ffffffff81709e09: loop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffff8172d550-ffffffff8172e015: loop_queue_work (STB_LOCAL)
ffffffff8172e0c2-ffffffff8172e105: loop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e9430)
Location: drivers/block/loop.c:2111
Inline: False
```
**Symbols:**

```
ffffffff817e9430-ffffffff817e94aa: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fdeb0)
Location: drivers/block/loop.c:2103
Inline: False
```
**Symbols:**

```
ffffffff817fdeb0-ffffffff817fdf2a: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e2a60)
Location: drivers/block/loop.c:2115
Inline: False
```
**Symbols:**

```
ffffffff817e2a60-ffffffff817e2ada: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void loop_queue_work(struct loop_device *lo, struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186fc10)
Location: drivers/block/loop.c:1033
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff8186fc10-ffffffff8186fe56: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void loop_queue_work(struct loop_device *lo, struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b65d0)
Location: drivers/block/loop.c:831
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff819b65d0-ffffffff819b67f7: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void loop_queue_work(struct loop_device *lo, struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2b7e0)
Location: drivers/block/loop.c:831
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff81b2b7e0-ffffffff81b2ba07: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void loop_queue_work(struct loop_device *lo, struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7baf0)
Location: drivers/block/loop.c:831
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff81b7baf0-ffffffff81b7bd07: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void loop_queue_work(struct loop_device *lo, struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bcfaf0)
Location: drivers/block/loop.c:827
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff81bcfaf0-ffffffff81bcfd36: loop_queue_work (STB_LOCAL)
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
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010922c28)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffff800010922c28-ffff8000109235c4: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a08930)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
c0a08930-c0a094f4: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c8fa0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
c0000000009c8fa0-c0000000009c9d6c: loop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a1e36)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffe0005a1e36-ffffffe0005a271e: loop_queue_work (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffff816f3330-ffffffff816f3df5: loop_queue_work (STB_LOCAL)
ffffffff816f3ea2-ffffffff816f3ee5: loop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffff816cd430-ffffffff816cdef5: loop_queue_work (STB_LOCAL)
ffffffff816cdfa2-ffffffff816cdfe5: loop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffff81720a10-ffffffff817214d5: loop_queue_work (STB_LOCAL)
ffffffff81721582-ffffffff817215c5: loop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void loop_queue_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2011
Inline: False
```
**Symbols:**

```
ffffffff8173bdd0-ffffffff8173c8a2: loop_queue_work (STB_LOCAL)
ffffffff8173c94f-ffffffff8173c992: loop_queue_work.cold (STB_LOCAL)
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
<code>struct loop_device *lo</code>
</li>
<li>
<b>Param added. </b>
<code>struct loop_cmd *cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kthread_work *work</code>
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
