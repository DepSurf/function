# Function: <code>iomap_unshare_actor</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
loff_t iomap_unshare_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac510)
Location: fs/iomap/buffered-io.c:869
Inline: True
```
**Symbols:**

```
ffffffff813ac620-ffffffff813ac654: iomap_unshare_actor (STB_LOCAL)
ffffffff813ac510-ffffffff813ac614: iomap_unshare_actor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
loff_t iomap_unshare_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bdae0)
Location: fs/iomap/buffered-io.c:844
Inline: True
```
**Symbols:**

```
ffffffff813bdbe0-ffffffff813bdc14: iomap_unshare_actor (STB_LOCAL)
ffffffff813bdae0-ffffffff813bdbde: iomap_unshare_actor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_unshare_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4cc0)
Location: fs/iomap/buffered-io.c:844
Inline: True
```
**Symbols:**

```
ffffffff813c4cc0-ffffffff813c4de7: iomap_unshare_actor (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
