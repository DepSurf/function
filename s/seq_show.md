# Function: <code>seq_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81281830)
Location: fs/proc/fd.c:19
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff817519f0)
Location: net/netfilter/nf_log.c:331
Inline: False
```
**Symbols:**

```
ffffffff81281830-ffffffff812819b8: seq_show (STB_LOCAL)
ffffffff817519f0-ffffffff81751af6: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812ae900)
Location: fs/proc/fd.c:19
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff817bda40)
Location: net/netfilter/nf_log.c:351
Inline: False
```
**Symbols:**

```
ffffffff812ae900-ffffffff812aea68: seq_show (STB_LOCAL)
ffffffff817bda40-ffffffff817bdb4b: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812c42e0)
Location: fs/proc/fd.c:19
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff817ed320)
Location: net/netfilter/nf_log.c:352
Inline: False
```
**Symbols:**

```
ffffffff812c42e0-ffffffff812c443c: seq_show (STB_LOCAL)
ffffffff817ed320-ffffffff817ed428: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812d1570)
Location: fs/proc/fd.c:19
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff8180dc60)
Location: net/netfilter/nf_log.c:354
Inline: True
```
**Symbols:**

```
ffffffff812d1570-ffffffff812d16c3: seq_show (STB_LOCAL)
ffffffff8180dc60-ffffffff8180dd6f: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812f5d70)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff8188d140)
Location: net/netfilter/nf_log.c:354
Inline: True
```
**Symbols:**

```
ffffffff812f5d70-ffffffff812f5ed2: seq_show (STB_LOCAL)
ffffffff8188d140-ffffffff8188d24f: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81323250)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff818e0b80)
Location: net/netfilter/nf_log.c:354
Inline: True
```
**Symbols:**

```
ffffffff81323250-ffffffff813233bb: seq_show (STB_LOCAL)
ffffffff818e0b80-ffffffff818e0c86: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8133a520)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff8190d6f0)
Location: net/netfilter/nf_log.c:354
Inline: True
```
**Symbols:**

```
ffffffff8133a520-ffffffff8133a68b: seq_show (STB_LOCAL)
ffffffff8190d6f0-ffffffff8190d7f6: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813626d0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff8196f320)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffff813626d0-ffffffff81362839: seq_show (STB_LOCAL)
ffffffff8196f320-ffffffff8196f415: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8137a930)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff819a5d50)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffff8137a930-ffffffff8137aa99: seq_show (STB_LOCAL)
ffffffff819a5d50-ffffffff819a5e45: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813c39c0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81a8e780)
Location: net/netfilter/nf_log.c:355
Inline: False
```
**Symbols:**

```
ffffffff813c39c0-ffffffff813c3b65: seq_show (STB_LOCAL)
ffffffff81a8e780-ffffffff81a8e880: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813d5b50)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81a987f0)
Location: net/netfilter/nf_log.c:355
Inline: False
```
**Symbols:**

```
ffffffff813d5b50-ffffffff813d5d26: seq_show (STB_LOCAL)
ffffffff81a987f0-ffffffff81a988f0: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813dcb60)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81a83b30)
Location: net/netfilter/nf_log.c:345
Inline: False
```
**Symbols:**

```
ffffffff813dcb60-ffffffff813dcd3a: seq_show (STB_LOCAL)
ffffffff81a83b30-ffffffff81a83c30: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8142e240)
Location: fs/proc/fd.c:21
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81b3d8f0)
Location: net/netfilter/nf_log.c:345
Inline: False
```
**Symbols:**

```
ffffffff8142e240-ffffffff8142e422: seq_show (STB_LOCAL)
ffffffff81b3d8f0-ffffffff81b3daee: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff814a7970)
Location: fs/proc/fd.c:21
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81cc9f00)
Location: net/netfilter/nf_log.c:345
Inline: False
```
**Symbols:**

```
ffffffff814a7970-ffffffff814a7b61: seq_show (STB_LOCAL)
ffffffff81cc9f00-ffffffff81cca0df: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8153d370)
Location: fs/proc/fd.c:22
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81e89b70)
Location: net/netfilter/nf_log.c:345
Inline: False
```
**Symbols:**

```
ffffffff8153d370-ffffffff8153d561: seq_show (STB_LOCAL)
ffffffff81e89b70-ffffffff81e89d4f: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81575650)
Location: fs/proc/fd.c:23
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81ee7b70)
Location: net/netfilter/nf_log.c:345
Inline: False
```
**Symbols:**

```
ffffffff81575650-ffffffff81575841: seq_show (STB_LOCAL)
ffffffff81ee7b70-ffffffff81ee7d66: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff815adfb0)
Location: fs/proc/fd.c:23
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81fab980)
Location: net/netfilter/nf_log.c:346
Inline: False
```
**Symbols:**

```
ffffffff815adfb0-ffffffff815ae18f: seq_show (STB_LOCAL)
ffffffff81fab980-ffffffff81fabb76: seq_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffff800010446eb0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffff800010c55400)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffff800010446eb0-ffff80001044709c: seq_show (STB_LOCAL)
ffff800010c55400-ffff800010c5553c: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c060bee8)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (c0d64ea0)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
c060bee8-c060c0a8: seq_show (STB_LOCAL)
c0d64ea0-c0d64fd0: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c00000000055cd50)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (c000000000d55860)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
c00000000055cd50-c00000000055d000: seq_show (STB_LOCAL)
c000000000d55860-c000000000d55a14: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffe0002dcc9a)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffe0007bf884)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffe0007bf884-ffffffe0007bf982: seq_show (STB_LOCAL)
ffffffe0002dcc9a-ffffffe0002dce42: seq_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81372f10)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81945bc0)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffff81372f10-ffffffff81373079: seq_show (STB_LOCAL)
ffffffff81945bc0-ffffffff81945cb5: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813639e0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff818ff6b0)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffff813639e0-ffffffff81363b49: seq_show (STB_LOCAL)
ffffffff818ff6b0-ffffffff818ff7a5: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813709e0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff81996d50)
Location: net/netfilter/nf_log.c:355
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999680)
Location: net/netfilter/nfnetlink_queue.c:1474
Inline: False
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b610)
Location: net/netfilter/nfnetlink_log.c:1082
Inline: False
```
**Symbols:**

```
ffffffff813709e0-ffffffff81370b49: seq_show (STB_LOCAL)
ffffffff81996d50-ffffffff81996e45: seq_show (STB_LOCAL)
ffffffff81999680-ffffffff819996bb: seq_show (STB_LOCAL)
ffffffff8199b610-ffffffff8199b645: seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int seq_show(struct seq_file *m, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813843c0)
Location: fs/proc/fd.c:20
Inline: False
```
```
In net/netfilter/nf_log.c (ffffffff819b9a10)
Location: net/netfilter/nf_log.c:355
Inline: True
```
**Symbols:**

```
ffffffff813843c0-ffffffff81384523: seq_show (STB_LOCAL)
ffffffff819b9a10-ffffffff819b9b05: seq_show (STB_LOCAL)
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
