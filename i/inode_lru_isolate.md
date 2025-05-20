# Function: <code>inode_lru_isolate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812280c0)
Location: fs/inode.c:691
Inline: False
```
**Symbols:**

```
ffffffff812280c0-ffffffff81228250: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812507f0)
Location: fs/inode.c:700
Inline: False
```
**Symbols:**

```
ffffffff812507f0-ffffffff81250980: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263890)
Location: fs/inode.c:702
Inline: False
```
**Symbols:**

```
ffffffff81263890-ffffffff81263a20: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271240)
Location: fs/inode.c:703
Inline: False
```
**Symbols:**

```
ffffffff81271240-ffffffff812713b8: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293b60)
Location: fs/inode.c:703
Inline: False
```
**Symbols:**

```
ffffffff81293b60-ffffffff81293cd8: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9e80)
Location: fs/inode.c:708
Inline: False
```
**Symbols:**

```
ffffffff812b9e80-ffffffff812ba000: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cee60)
Location: fs/inode.c:708
Inline: False
```
**Symbols:**

```
ffffffff812cee60-ffffffff812ceffa: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:721
Inline: False
```
**Symbols:**

```
ffffffff812ebd60-ffffffff812ebf27: inode_lru_isolate (STB_LOCAL)
ffffffff812ecfe6-ffffffff812ed006: inode_lru_isolate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fd8b0)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff812fd8b0-ffffffff812fda7e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336d20)
Location: fs/inode.c:733
Inline: False
```
**Symbols:**

```
ffffffff81336d20-ffffffff81336ede: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342660)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff81342660-ffffffff8134281e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348800)
Location: fs/inode.c:739
Inline: False
```
**Symbols:**

```
ffffffff81348800-ffffffff813489aa: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81396490)
Location: fs/inode.c:743
Inline: False
```
**Symbols:**

```
ffffffff81396490-ffffffff81396636: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814179a0)
Location: fs/inode.c:816
Inline: False
```
**Symbols:**

```
ffffffff814179a0-ffffffff81417b5e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a3140)
Location: fs/inode.c:815
Inline: False
```
**Symbols:**

```
ffffffff814a3140-ffffffff814a32fe: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d8290)
Location: fs/inode.c:818
Inline: False
```
**Symbols:**

```
ffffffff814d8290-ffffffff814d844e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150aa70)
Location: fs/inode.c:803
Inline: False
```
**Symbols:**

```
ffffffff8150aa70-ffffffff8150ac2e: inode_lru_isolate (STB_LOCAL)
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
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103aef18)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffff8000103aef18-ffff8000103af1c4: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058e4cc)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
c058e4cc-c058e728: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a9530)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
c0000000004a9530-c0000000004a9930: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000272cec)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffe000272cec-ffffffe000272fa0: inode_lru_isolate (STB_LOCAL)
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
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5e90)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff812f5e90-ffffffff812f605e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6ab0)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff812e6ab0-ffffffff812e6c7e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3ca0)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff812f3ca0-ffffffff812f3e6e: inode_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum lru_status inode_lru_isolate(struct list_head *item, struct list_lru_one *lru, spinlock_t *lru_lock, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305070)
Location: fs/inode.c:732
Inline: False
```
**Symbols:**

```
ffffffff81305070-ffffffff8130521f: inode_lru_isolate (STB_LOCAL)
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
