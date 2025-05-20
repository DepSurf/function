# Function: <code>__inode_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216e50)
Location: fs/namei.c:402
Inline: True
Direct callers:
  - fs/namei.c:inode_permission
```
**Symbols:**

```
ffffffff81216e50-ffffffff81216efe: __inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123dce0)
Location: fs/namei.c:404
Inline: True
Direct callers:
  - fs/namei.c:inode_permission
```
**Symbols:**

```
ffffffff8123dce0-ffffffff8123dd9c: __inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250ac0)
Location: fs/namei.c:404
Inline: True
Direct callers:
  - fs/namei.c:inode_permission
```
**Symbols:**

```
ffffffff81250ac0-ffffffff81250b7c: __inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cc40)
Location: fs/namei.c:404
Inline: True
Direct callers:
  - fs/namei.c:inode_permission
```
**Symbols:**

```
ffffffff8125cc40-ffffffff8125cd00: __inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127efb0)
Location: fs/namei.c:405
Inline: True
Direct callers:
  - fs/namei.c:inode_permission
```
**Symbols:**

```
ffffffff8127efb0-ffffffff8127f107: __inode_permission (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
