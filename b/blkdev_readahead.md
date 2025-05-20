# Function: <code>blkdev_readahead</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135eed0)
Location: fs/block_dev.c:616
Inline: False
```
**Symbols:**

```
ffffffff8135eed0-ffffffff8135eee7: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136c6b0)
Location: fs/block_dev.c:643
Inline: False
```
**Symbols:**

```
ffffffff8136c6b0-ffffffff8136c6c7: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81372fe0)
Location: fs/block_dev.c:647
Inline: False
```
**Symbols:**

```
ffffffff81372fe0-ffffffff81372ff7: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff815c5410)
Location: block/fops.c:345
Inline: False
```
**Symbols:**

```
ffffffff815c5410-ffffffff815c5427: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff8166fe50)
Location: block/fops.c:380
Inline: False
```
**Symbols:**

```
ffffffff8166fe50-ffffffff8166fe6f: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff8172b3a0)
Location: block/fops.c:399
Inline: False
```
**Symbols:**

```
ffffffff8172b3a0-ffffffff8172b3bf: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff81767460)
Location: block/fops.c:400
Inline: False
```
**Symbols:**

```
ffffffff81767460-ffffffff8176747f: blkdev_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkdev_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff817a91e0)
Location: block/fops.c:438
Inline: False
```
**Symbols:**

```
ffffffff817a91e0-ffffffff817a91ff: blkdev_readahead (STB_LOCAL)
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
