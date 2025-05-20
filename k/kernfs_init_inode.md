# Function: <code>kernfs_init_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812890b0)
Location: fs/kernfs/inode.c:286
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812b65b0)
Location: fs/kernfs/inode.c:290
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cbde0)
Location: fs/kernfs/inode.c:217
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d9234)
Location: fs/kernfs/inode.c:217
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fda94)
Location: fs/kernfs/inode.c:217
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b6f0)
Location: fs/kernfs/inode.c:217
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81342a50)
Location: fs/kernfs/inode.c:217
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136abc0)
Location: fs/kernfs/inode.c:199
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382d80)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_init_inode(struct kernfs_node *kn, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd260)
Location: fs/kernfs/inode.c:200
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
**Symbols:**

```
ffffffff813cd260-ffffffff813cd361: kernfs_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_init_inode(struct kernfs_node *kn, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813dee90)
Location: fs/kernfs/inode.c:200
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
**Symbols:**

```
ffffffff813dee90-ffffffff813def91: kernfs_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e6001)
Location: fs/kernfs/inode.c:202
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437c01)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b296b)
Location: fs/kernfs/inode.c:202
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8154954b)
Location: fs/kernfs/inode.c:200
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8158112b)
Location: fs/kernfs/inode.c:200
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9bdb)
Location: fs/kernfs/inode.c:199
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff800010451280)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0614270)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0000000005698f0)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e4134)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b360)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136be30)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378e30)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138c8e0)
Location: fs/kernfs/inode.c:198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
