# Function: <code>sbitmap_finish_wait</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150cbd0)
Location: lib/sbitmap.c:701
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff8150cbd0-ffffffff8150cc05: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b350)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff8153b350-ffffffff8153b385: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c130)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff8155c130-ffffffff8155c165: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5bb0)
Location: lib/sbitmap.c:680
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff815e5bb0-ffffffff815e5be5: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81609f70)
Location: lib/sbitmap.c:675
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81609f70-ffffffff81609fa5: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed000)
Location: lib/sbitmap.c:701
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff815ed000-ffffffff815ed035: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81659f20)
Location: lib/sbitmap.c:701
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81659f20-ffffffff81659f55: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81772650)
Location: lib/sbitmap.c:810
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81772650-ffffffff81772691: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818a2eb0)
Location: lib/sbitmap.c:768
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff818a2eb0-ffffffff818a2eeb: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818e53a0)
Location: lib/sbitmap.c:760
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff818e53a0-ffffffff818e53db: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8192c3a0)
Location: lib/sbitmap.c:755
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff8192c3a0-ffffffff8192c3db: sbitmap_finish_wait (STB_GLOBAL)
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
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff80001066a020)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffff80001066a020-ffff80001066a084: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0811de0)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
c0811de0-c0811e38: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081ee40)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
c00000000081ee40-c00000000081eeb4: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe00049449a)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffe00049449a-ffffffe0004944da: sbitmap_finish_wait (STB_GLOBAL)
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
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554720)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81554720-ffffffff81554755: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815449a0)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff815449a0-ffffffff815449d5: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81550460)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81550460-ffffffff81550495: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sbitmap_finish_wait(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a2a0)
Location: lib/sbitmap.c:697
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff8156a2a0-ffffffff8156a2d5: sbitmap_finish_wait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
