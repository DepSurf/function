# Function: <code>mqueue_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8132c4c0)
Location: ipc/mqueue.c:212
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_fill_super
  - ipc/mqueue.c:mqueue_create
```
**Symbols:**

```
ffffffff8132c4c0-ffffffff8132c7a5: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81361140)
Location: ipc/mqueue.c:212
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81361140-ffffffff813613fe: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81377940)
Location: ipc/mqueue.c:212
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81377940-ffffffff81377bf9: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138b4c0)
Location: ipc/mqueue.c:215
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8138b4c0-ffffffff8138b776: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b0850)
Location: ipc/mqueue.c:215
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff813b0850-ffffffff813b0b06: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e2ea0)
Location: ipc/mqueue.c:215
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff813e2ea0-ffffffff813e31e0: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fd680)
Location: ipc/mqueue.c:215
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff813fd680-ffffffff813fd9c6: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81429ca0)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81429ca0-ffffffff8142a01b: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814439d0)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814439d0-ffffffff81443d4b: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814946a0)
Location: ipc/mqueue.c:291
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814946a0-ffffffff81494a4e: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b2000)
Location: ipc/mqueue.c:291
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814b2000-ffffffff814b23ae: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b7e80)
Location: ipc/mqueue.c:291
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814b7e80-ffffffff814b8220: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81510690)
Location: ipc/mqueue.c:291
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81510690-ffffffff81510a49: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8159f930)
Location: ipc/mqueue.c:290
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8159f930-ffffffff8159fcd6: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816491d0)
Location: ipc/mqueue.c:290
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff816491d0-ffffffff81649576: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81681730)
Location: ipc/mqueue.c:290
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81681730-ffffffff81681ad6: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816bdb30)
Location: ipc/mqueue.c:290
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff816bdb30-ffffffff816bdeb7: mqueue_get_inode (STB_LOCAL)
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
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff8000105299c8)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffff8000105299c8-ffff800010529cf4: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e2698)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
c06e2698-c06e29b4: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c0000000006749e0)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
c0000000006749e0-c000000000674e18: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038d36a)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffe00038d36a-ffffffe00038d642: mqueue_get_inode (STB_LOCAL)
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
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143bfb0)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8143bfb0-ffffffff8143c32b: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142ca20)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8142ca20-ffffffff8142cd9b: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81438150)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81438150-ffffffff814384cb: mqueue_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *mqueue_get_inode(struct super_block *sb, struct ipc_namespace *ipc_ns, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144c680)
Location: ipc/mqueue.c:231
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8144c680-ffffffff8144c9fe: mqueue_get_inode (STB_LOCAL)
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
