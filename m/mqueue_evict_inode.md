# Function: <code>mqueue_evict_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8132cef0)
Location: ipc/mqueue.c:370
Inline: True
```
**Symbols:**

```
ffffffff8132cef0-ffffffff8132d161: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81361b60)
Location: ipc/mqueue.c:368
Inline: True
```
**Symbols:**

```
ffffffff81361b60-ffffffff81361de8: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81378360)
Location: ipc/mqueue.c:368
Inline: True
```
**Symbols:**

```
ffffffff81378360-ffffffff813785e8: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138cfd0)
Location: ipc/mqueue.c:371
Inline: True
```
**Symbols:**

```
ffffffff8138cfd0-ffffffff8138d26d: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b2380)
Location: ipc/mqueue.c:371
Inline: True
```
**Symbols:**

```
ffffffff813b2380-ffffffff813b2623: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:388
Inline: True
```
**Symbols:**

```
ffffffff813e2c30-ffffffff813e2e96: mqueue_evict_inode (STB_LOCAL)
ffffffff813e34b5-ffffffff813e34ed: mqueue_evict_inode.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff813fba40)
Location: ipc/mqueue.c:388
Inline: True
```
**Symbols:**

```
ffffffff813fba10-ffffffff813fbc76: mqueue_evict_inode (STB_LOCAL)
ffffffff813fdc67-ffffffff813fdc9f: mqueue_evict_inode.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:438
Inline: False
```
**Symbols:**

```
ffffffff814284e0-ffffffff814287f8: mqueue_evict_inode (STB_LOCAL)
ffffffff8142a2a7-ffffffff8142a2df: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffff81442210-ffffffff81442528: mqueue_evict_inode (STB_LOCAL)
ffffffff81443fd7-ffffffff8144400f: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:497
Inline: False
```
**Symbols:**

```
ffffffff81493b50-ffffffff81493eac: mqueue_evict_inode (STB_LOCAL)
ffffffff81494de7-ffffffff81494e1f: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:497
Inline: False
```
**Symbols:**

```
ffffffff814b14b0-ffffffff814b180f: mqueue_evict_inode (STB_LOCAL)
ffffffff81befb54-ffffffff81befb8c: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:497
Inline: False
```
**Symbols:**

```
ffffffff814b7330-ffffffff814b7687: mqueue_evict_inode (STB_LOCAL)
ffffffff81be1bfb-ffffffff81be1c33: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:500
Inline: False
```
**Symbols:**

```
ffffffff8150fc70-ffffffff8150fff5: mqueue_evict_inode (STB_LOCAL)
ffffffff81cd2dc6-ffffffff81cd2e30: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a16f0)
Location: ipc/mqueue.c:512
Inline: False
```
**Symbols:**

```
ffffffff815a16f0-ffffffff815a192f: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164b160)
Location: ipc/mqueue.c:512
Inline: False
```
**Symbols:**

```
ffffffff8164b160-ffffffff8164b39f: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:512
Inline: False
```
**Symbols:**

```
ffffffff816836b0-ffffffff81683aac: mqueue_evict_inode (STB_LOCAL)
ffffffff820f2cf2-ffffffff820f2d22: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:512
Inline: False
```
**Symbols:**

```
ffffffff816bfad0-ffffffff816bfecc: mqueue_evict_inode (STB_LOCAL)
ffffffff821cff8a-ffffffff821cffba: mqueue_evict_inode.cold (STB_LOCAL)
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
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052bbb0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffff80001052bbb0-ffff80001052bfb0: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e3c54)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
c06e3c54-c06e3f8c: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000678270)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
c000000000678270-c0000000006787b8: mqueue_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038d018)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffe00038d018-ffffffe00038d36a: mqueue_evict_inode (STB_LOCAL)
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
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffff8143a7f0-ffffffff8143ab08: mqueue_evict_inode (STB_LOCAL)
ffffffff8143c5b7-ffffffff8143c5ef: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffff8142b260-ffffffff8142b578: mqueue_evict_inode (STB_LOCAL)
ffffffff8142d027-ffffffff8142d05f: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffff81436990-ffffffff81436ca8: mqueue_evict_inode (STB_LOCAL)
ffffffff81438757-ffffffff8143878f: mqueue_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mqueue_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:437
Inline: False
```
**Symbols:**

```
ffffffff8144f0a0-ffffffff8144f3b3: mqueue_evict_inode (STB_LOCAL)
ffffffff8144f8e7-ffffffff8144f91f: mqueue_evict_inode.cold (STB_LOCAL)
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
