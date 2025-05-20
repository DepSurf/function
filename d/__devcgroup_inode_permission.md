# Function: <code>__devcgroup_inode_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __devcgroup_inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81395680)
Location: security/device_cgroup.c:837
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81395680-ffffffff813956d1: __devcgroup_inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __devcgroup_inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813d13d0)
Location: security/device_cgroup.c:837
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff813d13d0-ffffffff813d141c: __devcgroup_inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __devcgroup_inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813e8b00)
Location: security/device_cgroup.c:837
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff813e8b00-ffffffff813e8b4c: __devcgroup_inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __devcgroup_inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813f4ea0)
Location: security/device_cgroup.c:837
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff813f4ea0-ffffffff813f4ee8: __devcgroup_inode_permission (STB_GLOBAL)
```
</details>
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
</ul>
