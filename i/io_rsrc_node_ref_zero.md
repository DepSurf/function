# Function: <code>io_rsrc_node_ref_zero</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_rsrc_node_ref_zero(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390b90)
Location: fs/io_uring.c:7617
Inline: False
```
**Symbols:**

```
ffffffff81390b90-ffffffff81390c9c: io_rsrc_node_ref_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void io_rsrc_node_ref_zero(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:7720
Inline: False
```
**Symbols:**

```
ffffffff813de520-ffffffff813de658: io_rsrc_node_ref_zero (STB_LOCAL)
ffffffff81cc586c-ffffffff81cc58a3: io_rsrc_node_ref_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_rsrc_node_ref_zero(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f126)
Location: io_uring/io_uring.c:9029
Inline: False
```
**Symbols:**

```
ffffffff81e8f126-ffffffff81e8f268: io_rsrc_node_ref_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void io_rsrc_node_ref_zero(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:227
Inline: False
```
**Symbols:**

```
ffffffff817a0130-ffffffff817a028c: io_rsrc_node_ref_zero (STB_LOCAL)
ffffffff82077990-ffffffff820779c7: io_rsrc_node_ref_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_rsrc_node_ref_zero(struct io_rsrc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:171
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff820f7a90-ffffffff820f7aa5: io_rsrc_node_ref_zero.cold (STB_LOCAL)
ffffffff817e1e90-ffffffff817e2034: io_rsrc_node_ref_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_rsrc_node_ref_zero(struct io_rsrc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:176
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff821d5429-ffffffff821d5444: io_rsrc_node_ref_zero.cold (STB_LOCAL)
ffffffff81826230-ffffffff818263bc: io_rsrc_node_ref_zero (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_rsrc_node *node</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_ref *ref</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
