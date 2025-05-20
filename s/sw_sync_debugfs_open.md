# Function: <code>sw_sync_debugfs_open</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8162c680)
Location: drivers/dma-buf/sw_sync.c:269
Inline: False
```
**Symbols:**

```
ffffffff8162c680-ffffffff8162c74b: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81641c10)
Location: drivers/dma-buf/sw_sync.c:269
Inline: False
```
**Symbols:**

```
ffffffff81641c10-ffffffff81641d20: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816aa630)
Location: drivers/dma-buf/sw_sync.c:305
Inline: False
```
**Symbols:**

```
ffffffff816aa630-ffffffff816aa741: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:305
Inline: False
```
**Symbols:**

```
ffffffff816e6b40-ffffffff816e6c41: sw_sync_debugfs_open (STB_LOCAL)
ffffffff816e7378-ffffffff816e7390: sw_sync_debugfs_open.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:304
Inline: False
```
**Symbols:**

```
ffffffff81709d50-ffffffff81709e51: sw_sync_debugfs_open (STB_LOCAL)
ffffffff8170a708-ffffffff8170a720: sw_sync_debugfs_open.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:295
Inline: False
```
**Symbols:**

```
ffffffff81745560-ffffffff81745661: sw_sync_debugfs_open (STB_LOCAL)
ffffffff81745f5b-ffffffff81745f73: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff817696e0-ffffffff817697e1: sw_sync_debugfs_open (STB_LOCAL)
ffffffff8176a0ba-ffffffff8176a0d2: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8182ba00)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff8182ba00-ffffffff8182ba6f: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8183c900)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff8183c900-ffffffff8183c96f: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff8181fae0-ffffffff8181fbe1: sw_sync_debugfs_open (STB_LOCAL)
ffffffff81c07f53-ffffffff81c07f6b: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff818aa1a0-ffffffff818aa2a1: sw_sync_debugfs_open (STB_LOCAL)
ffffffff81d0bd51-ffffffff81d0bd69: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff819f49c0-ffffffff819f4adb: sw_sync_debugfs_open (STB_LOCAL)
ffffffff81ed4bdb-ffffffff81ed4bf3: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81b71e20)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff81b71e20-ffffffff81b71f4f: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5650)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff81bc5650-ffffffff81bc56d9: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81c19e70)
Location: drivers/dma-buf/sw_sync.c:331
Inline: False
```
**Symbols:**

```
ffffffff81c19e70-ffffffff81c19ef9: sw_sync_debugfs_open (STB_LOCAL)
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
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffff80001096ae28)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffff80001096ae28-ffff80001096af38: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c0a40dd8)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
c0a40dd8-c0a40ef4: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c000000000a23bd0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
c000000000a23bd0-c000000000a23d48: sw_sync_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffe0005d63bc)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffe0005d63bc-ffffffe0005d6458: sw_sync_debugfs_open (STB_LOCAL)
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
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff8171ddd0-ffffffff8171ded1: sw_sync_debugfs_open (STB_LOCAL)
ffffffff8171e7aa-ffffffff8171e7c2: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff816f7230-ffffffff816f7331: sw_sync_debugfs_open (STB_LOCAL)
ffffffff816f7bf4-ffffffff816f7c0c: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff8175cba0-ffffffff8175cca1: sw_sync_debugfs_open (STB_LOCAL)
ffffffff8175d57a-ffffffff8175d592: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sw_sync_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:293
Inline: False
```
**Symbols:**

```
ffffffff81778240-ffffffff81778341: sw_sync_debugfs_open (STB_LOCAL)
ffffffff81778c18-ffffffff81778c30: sw_sync_debugfs_open.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
