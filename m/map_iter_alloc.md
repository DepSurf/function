# Function: <code>map_iter_alloc</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811c05e4)
Location: kernel/bpf/inode.c:176
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811d1a44)
Location: kernel/bpf/inode.c:176
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811e5d76)
Location: kernel/bpf/inode.c:173
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811f24c6)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct map_iter *map_iter_alloc(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812140e0)
Location: kernel/bpf/inode.c:195
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff812140e0-ffffffff81214145: map_iter_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct map_iter *map_iter_alloc(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215920)
Location: kernel/bpf/inode.c:196
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff81215920-ffffffff81215985: map_iter_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct map_iter *map_iter_alloc(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218510)
Location: kernel/bpf/inode.c:197
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff81218510-ffffffff81218575: map_iter_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct map_iter *map_iter_alloc(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124eb40)
Location: kernel/bpf/inode.c:197
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff8124eb40-ffffffff8124eba5: map_iter_alloc (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff81295cd6)
Location: kernel/bpf/inode.c:197
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff812f0b16)
Location: kernel/bpf/inode.c:197
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff8131d6a6)
Location: kernel/bpf/inode.c:197
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff8133fa1a)
Location: kernel/bpf/inode.c:194
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffff800010275d54)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (c04a842c)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (c00000000031e094)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffe0001ae352)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811eaae6)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811dd8a6)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811e88b6)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff811f6c66)
Location: kernel/bpf/inode.c:174
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_open
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
