# Function: <code>full_proxy_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81352cb0)
Location: fs/debugfs/file.c:175
Inline: False
```
**Symbols:**

```
ffffffff81352cb0-ffffffff81352d34: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81368f60)
Location: fs/debugfs/file.c:172
Inline: False
```
**Symbols:**

```
ffffffff81368f60-ffffffff81368fe4: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137d5f0)
Location: fs/debugfs/file.c:172
Inline: False
```
**Symbols:**

```
ffffffff8137d5f0-ffffffff8137d669: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a3480)
Location: fs/debugfs/file.c:213
Inline: False
```
**Symbols:**

```
ffffffff813a3480-ffffffff813a34e8: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d27a0)
Location: fs/debugfs/file.c:233
Inline: False
```
**Symbols:**

```
ffffffff813d27a0-ffffffff813d2808: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ece90)
Location: fs/debugfs/file.c:234
Inline: False
```
**Symbols:**

```
ffffffff813ece90-ffffffff813ecef8: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (0)
Location: fs/debugfs/file.c:234
Inline: False
```
**Symbols:**

```
ffffffff81419050-ffffffff814190c5: full_proxy_poll (STB_LOCAL)
ffffffff8141971a-ffffffff81419724: full_proxy_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81432f20)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffff81432f20-ffffffff81432f8b: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482ca0)
Location: fs/debugfs/file.c:243
Inline: False
```
**Symbols:**

```
ffffffff81482ca0-ffffffff81482d0a: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0330)
Location: fs/debugfs/file.c:243
Inline: False
```
**Symbols:**

```
ffffffff814a0330-ffffffff814a039a: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6400)
Location: fs/debugfs/file.c:243
Inline: False
```
**Symbols:**

```
ffffffff814a6400-ffffffff814a646a: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fde80)
Location: fs/debugfs/file.c:245
Inline: False
```
**Symbols:**

```
ffffffff814fde80-ffffffff814fdeea: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158eaa0)
Location: fs/debugfs/file.c:245
Inline: False
```
**Symbols:**

```
ffffffff8158eaa0-ffffffff8158eb0f: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81635b50)
Location: fs/debugfs/file.c:245
Inline: False
```
**Symbols:**

```
ffffffff81635b50-ffffffff81635bbf: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166de60)
Location: fs/debugfs/file.c:245
Inline: False
```
**Symbols:**

```
ffffffff8166de60-ffffffff8166ded5: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a8640)
Location: fs/debugfs/file.c:337
Inline: False
```
**Symbols:**

```
ffffffff816a8640-ffffffff816a86b8: full_proxy_poll (STB_LOCAL)
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
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010518758)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffff800010518758-ffff8000105187e8: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d2eac)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
c06d2eac-c06d2f20: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c0000000006618d0)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
c0000000006618d0-c0000000006619a8: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381bc8)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffe000381bc8-ffffffe000381c6a: full_proxy_poll (STB_LOCAL)
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
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142b500)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffff8142b500-ffffffff8142b56b: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141bf80)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffff8141bf80-ffffffff8141bfeb: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814276a0)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffff814276a0-ffffffff8142770b: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t full_proxy_poll(struct file *filp, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143e560)
Location: fs/debugfs/file.c:237
Inline: False
```
**Symbols:**

```
ffffffff8143e560-ffffffff8143e5cb: full_proxy_poll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
