# Function: <code>mqueue_get_tree</code>

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
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814271b0)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff814271b0-ffffffff814271d7: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81440ef0)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff81440ef0-ffffffff81440f0e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81491cc0)
Location: ipc/mqueue.c:423
Inline: False
```
**Symbols:**

```
ffffffff81491cc0-ffffffff81491cde: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814af320)
Location: ipc/mqueue.c:423
Inline: False
```
**Symbols:**

```
ffffffff814af320-ffffffff814af33e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b5160)
Location: ipc/mqueue.c:423
Inline: False
```
**Symbols:**

```
ffffffff814b5160-ffffffff814b517e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150d820)
Location: ipc/mqueue.c:426
Inline: False
```
**Symbols:**

```
ffffffff8150d820-ffffffff8150d83e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:425
Inline: False
```
**Symbols:**

```
ffffffff815a0250-ffffffff815a02c5: mqueue_get_tree (STB_LOCAL)
ffffffff81e85f29-ffffffff81e85f3e: mqueue_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:425
Inline: False
```
**Symbols:**

```
ffffffff81649ba0-ffffffff81649c15: mqueue_get_tree (STB_LOCAL)
ffffffff82073067-ffffffff8207307c: mqueue_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:425
Inline: False
```
**Symbols:**

```
ffffffff81682100-ffffffff81682175: mqueue_get_tree (STB_LOCAL)
ffffffff820f2cb3-ffffffff820f2cc8: mqueue_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:425
Inline: False
```
**Symbols:**

```
ffffffff816be500-ffffffff816be575: mqueue_get_tree (STB_LOCAL)
ffffffff821cff4b-ffffffff821cff60: mqueue_get_tree.cold (STB_LOCAL)
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
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff800010529360)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffff800010529360-ffff80001052939c: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e2eec)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
c06e2eec-c06e2f18: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000675870)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
c000000000675870-c0000000006758b4: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038c93c)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffe00038c93c-ffffffe00038c972: mqueue_get_tree (STB_LOCAL)
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
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814394d0)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff814394d0-ffffffff814394ee: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81429f40)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff81429f40-ffffffff81429f5e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81435670)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff81435670-ffffffff8143568e: mqueue_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mqueue_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144cfd0)
Location: ipc/mqueue.c:363
Inline: False
```
**Symbols:**

```
ffffffff8144cfd0-ffffffff8144cfee: mqueue_get_tree (STB_LOCAL)
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
