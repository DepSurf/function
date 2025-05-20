# Function: <code>lo_rw_aio_do_completion</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166fda0)
Location: drivers/block/loop.c:466
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff8166fda0-ffffffff8166fdd0: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ab5c0)
Location: drivers/block/loop.c:488
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff816ab5c0-ffffffff816ab5f3: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cbd30)
Location: drivers/block/loop.c:489
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff816cbd30-ffffffff816cbd63: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81707330)
Location: drivers/block/loop.c:489
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff81707330-ffffffff81707364: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172b580)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff8172b580-ffffffff8172b5b4: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e7540)
Location: drivers/block/loop.c:504
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff817e7540-ffffffff817e7577: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fc170)
Location: drivers/block/loop.c:501
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff817fc170-ffffffff817fc1a7: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e1220)
Location: drivers/block/loop.c:543
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff817e1220-ffffffff817e1257: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186dbc9)
Location: drivers/block/loop.c:533
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff8186cb30-ffffffff8186cb67: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b5640)
Location: drivers/block/loop.c:374
Inline: True
```
**Symbols:**

```
ffffffff819b5640-ffffffff819b5683: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b29fc0)
Location: drivers/block/loop.c:374
Inline: True
```
**Symbols:**

```
ffffffff81b29fc0-ffffffff81b2a003: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7a1f0)
Location: drivers/block/loop.c:374
Inline: True
```
**Symbols:**

```
ffffffff81b7a1f0-ffffffff81b7a233: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bce150)
Location: drivers/block/loop.c:370
Inline: True
```
**Symbols:**

```
ffffffff81bce150-ffffffff81bce193: lo_rw_aio_do_completion (STB_LOCAL)
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
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010922218)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffff800010922218-ffff800010922280: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a06f4c)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
c0a06f4c-c0a06fa8: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c6630)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
c0000000009c6630-c0000000009c66b4: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a04d2)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffe0005a04d2-ffffffe0005a0528: lo_rw_aio_do_completion (STB_LOCAL)
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
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f1360)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff816f1360-ffffffff816f1394: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cb460)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff816cb460-ffffffff816cb494: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171ea40)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff8171ea40-ffffffff8171ea74: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81739e70)
Location: drivers/block/loop.c:491
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff81739e70-ffffffff81739ea4: lo_rw_aio_do_completion (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
